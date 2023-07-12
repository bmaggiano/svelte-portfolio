<script>
	import '../app.postcss';
	import { Footer, FooterCopyright, FooterLinkGroup, FooterLink } from 'flowbite-svelte';
</script>

<div class="navContainer">
	<img src="./smaller.jpg" alt="brandon maggiano" class="headshot" />
	<h1>Portfolio</h1>
	<nav>
		<a href="/">Home</a>
		<a href="/about">About</a>
		<a href="/projects">Projects</a>
	</nav>
</div>

<slot />

<Footer>
    <FooterCopyright href="/" by="Brandon Maggiano™" year={2023} />
    <FooterLinkGroup ulClass="flex flex-wrap items-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0">
      <FooterLink href="/">About</FooterLink>
      <FooterLink href="/">Privacy Policy</FooterLink>
      <FooterLink href="/">Licensing</FooterLink>
      <FooterLink href="/">Contact</FooterLink>
    </FooterLinkGroup>
  </Footer>

<style>
	h1 {
		font-family: sans-serif;
        font-size: 2rem;
        padding: 1rem;
	}
	.navContainer {
		display: flex;
		align-items: center;
	}
	nav {
		padding-left: 2rem;
	}
	a {
		font-family: sans-serif;
		padding-left: 2rem;
		text-decoration: none;
		color: rgb(255, 60, 0);
		letter-spacing: 0.2rem;
		font-weight: bold;
	}
	img {
		height: 3rem;
		border-radius: 5rem;
		margin-right: 0.5rem;
	}
	@media (max-width: 600px) {
		.navContainer {
			flex-direction: column;
		}
		nav {
			padding-left: 0;
		}
	}
</style>

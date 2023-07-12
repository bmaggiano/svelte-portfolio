<style>
    h1 {
        font-family: sans-serif;
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
        letter-spacing: .2rem;
        font-weight: bold;
    }
    img {
        height: 3rem;
        border-radius: 5rem;
        margin-right: 1rem;
    }
</style>

<div class="navContainer">
        <img
            src="./smaller.jpg"
            alt="brandon maggiano"
            class="headshot"
            />
        <h1>My Portfolio</h1>
    <nav>
        <a href="/">Home</a>
        <a href="/about">About</a>
        <a href="/projects">Projects</a>
    </nav>
</div>

<slot></slot>
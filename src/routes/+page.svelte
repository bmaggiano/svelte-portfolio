<script>
    import { Blockquote } from 'flowbite-svelte'
    import '../styles.css'
    import HeadInfo from './HeadInfo.svelte';
  </script>

<!-- Sets the title of the page -->
  <HeadInfo title="Portfolio Home" />

<!-- Our header and this layout will be consistent across all pages -->
<header class="header">
    <div class="right-side">
        <div class="title">
            <h1>Built using the power of <br/> Svelte & Flowbite</h1><br/>
              
              <Blockquote size='xl'>
              "Flowbite is just awesome. It contains tons of predesigned components and pages starting from login screen to complex dashboard. Perfect choice for your next SaaS application."
              </Blockquote>
        </div>
        <img
        class="headshot"
        src="./sveltelogo.png"
        alt="Svelte logo"
        />
    </div>
</header>

<!-- similar to mint.com subheader -->
<section class="subheader">
    <h2>See why Svelte is averaging 500,000+ weekly downloads! <a href="https://svelte.dev/" target="_blank">Learn More</a></h2>
</section>


<section class="content">

    <h3 class="font-semibold">Check out some of my recent projects</h3>
    <br/>
    <br/>
    <br/>

    <div class="project-left">
        <img 
            class="project"
            src="./project1.png"
            alt="cell phone with igcap.dev pulled up"
            />
        <div class="description">
            <h4>IG Caption Generator</h4>
            <p>Using the power of ChatGPT and Replicate, you're able to get custom generated captions based off a number of pre set vibes.</p>
            <br/>
            <a href="https://igcap.dev" target="_blank">Visit Site</a>
        </div>
    </div>

    <div class="project-left middle">
        <div class="description">
            <h4>Super Showdown</h4>
            <p>A fun card game in which you'll need to choose the correct hero to defeat a given opponent. Incorporating many technologies such as Prisma, Clerk, ChatGPT, and much more! </p>
            <br/>
            <a href="https://super-showdown.vercel.app/" target="_blank">Visit Site</a>
                </div>
        <img 
            class="project"
            src="./project2.png"
            alt="cell phone with the home page of super showdown"
            />
    </div>

    <div class="project-left">
        <img 
            class="project"
            src="./project3.png"
            alt="cell phone with the casual's caddie website home page"
            />
        <div class="description">
            <h4>The Casual's Caddie</h4>
            <p>Keeping track of your golf game just got easier! With our tracking system, you'll never be in doubt as you stand on the tee box again.</p>
            <br/>
            <a href="https://the-casuals-caddie.herokuapp.com/" target="_blank">Visit Site</a>        
        </div>
    </div>
    
    <div class="github">
        <a href="https://github.com/bmaggiano" target="_blank">
            <img
            src="./github.png"
            alt="github logo"
            class="github-logo"
            />
        </a>
            <hr/>
        <h5>The projects dont stop there, check out my github.</h5>
        <p>I have over 26 repos ranging from front end, to back end, to full stack and even project collaboration with others!</p>
    </div>

</section>

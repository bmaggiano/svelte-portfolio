<style>
    h1, h2, h3, h4, h5, h6, p, a {
        font-family: sans-serif;
    }
    h1 {
        font-size: 3rem;
        font-weight: bold;
        color: black;
    }
    .subheader a {
        margin-left: 1rem;
        color: white;
        text-decoration: underline;
    }
    h2 {
        font-size: 1.2rem;
        padding: 1rem;
    }
    h3 {
        text-align: center;
        padding-top: 1rem;
        font-size: 2rem;
    }
    h5 {
        font-size: 2rem;
        letter-spacing: .1rem;
        margin: 1rem;
    }
    .header {
        display: flex;
        align-items: center;
        justify-content: space-around;
        background-color: rgb(203, 242, 255);
    }
    .headshot {
        height: 15rem;
    }
    .right-side {
        display: flex;
        align-items: center;
        justify-content: space-around;
        margin-top: 4rem;
        margin-bottom: 4rem;
        width: 50rem;
    }
    .subheader {
        background-color: rgb(255, 60, 0);
        color: white;
        text-align: center;
        padding: .01rem;
    }
    .content {
        background-color: rgba(203, 242, 255, 0.637);
        padding: .1rem;
    }
    .project-left {
        display: flex;
        align-items: center;
        justify-content: space-evenly;
        max-width: 50rem;
        margin: auto;
        margin-bottom: 5rem;
    }
    .description a {
        text-decoration: none;
        background-color: rgb(255, 60, 0);
        padding: .8rem;
        border-radius: .5rem;
        border: none;
        color: white;
        font-size: large;
        cursor: pointer;
    }
    .description {
        margin: 5rem;
    }
    .description h4{
        font-size: 2.5rem;
        margin-bottom: 1.5rem;
    }
    .description p {
        font-size: 1.1rem;
    }
    .project {
        width: 16rem;
    }
    .github {
        text-align: center;
        margin-bottom: 5rem;
    }
    .github-logo {
        width: 3rem;
        margin: 0 auto;
    }
    hr {
    margin: 0 auto;
    width: 5%;
    background-color: darkgray;
    border: none;
    height: 2px;
    margin-top: 1rem;
}


    @media (max-width: 600px) {
    .title {
        padding: 0;
        text-align: center;
        margin-bottom: 1rem;
        margin-top: 0;
    }
    .right-side {
        flex-direction: column;
    }
    .project-left {
        flex-direction: column;
        max-width: 100%;
    }
    .project-left .project {
        margin-bottom: 1rem;
    }
    .project-left .description {
        margin: 1rem;
    }
    .description {
        text-align: center;
    }
    .middle {
        flex-direction: column-reverse;
    }
}
</style>

<script>
    import { Blockquote } from 'flowbite-svelte'
  </script>

<div class="header">
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
        alt="Brandon Maggiano"
        />
    </div>
</div>

<div class="subheader">
    <h2>See why Svelte is averaging 500,000+ weekly downloads! <a href="https://svelte.dev/" target="_blank">Learn More</a></h2>
</div>


<div class="content">

    <h3 class="font-semibold">Check out some of my recent projects</h3>
    <br/>
    <br/>
    <br/>

    <div class="project-left">
        <img 
            class="project"
            src="./project1.png"
            alt=""
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
            alt=""
            />
    </div>

    <div class="project-left">
        <img 
            class="project"
            src="./project3.png"
            alt=""
            />
        <div class="description">
            <h4>The Casual's Caddie</h4>
            <p>Keeping track of your golf game just got easier! With our tracking system, you'll never be in doubt as you stand on the tee box again.</p>
            <br/>
            <a href="https://the-casuals-caddie.herokuapp.com/" target="_blank">Visit Site</a>        
        </div>
    </div>
    
    <div class="github">
        <!-- I want github logo to go here -->
        <a href="https://github.com/bmaggiano" target="_blank">
            <img
            src="./github.png"
            alt=""
            class="github-logo"
            />
        </a>
            <hr/>
        <h5>The Projects dont stop there, check out my github.</h5>
        <p>I have over 26 repos ranging from front end, to back end, to full stack and even project collaboration with others!</p>
    </div>

</div>

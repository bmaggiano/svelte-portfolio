<script>
    import { Blockquote } from 'flowbite-svelte'
    import '../../styles.css'
  </script>

<div class="header">
    <div class="right-side">
        <div class="title">
            <h1>About Me</h1><br/>
              
              <Blockquote size='xl'>
              My journey started on 4/21/2022 when I wrote my very <br/> first line of code... "Hello World"
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
    <h2>Making a career change can be one of the most daunting desicions of a person's life...</h2>
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
        <h5>The projects dont stop there, check out my github.</h5>
        <p>I have over 26 repos ranging from front end, to back end, to full stack and even project collaboration with others!</p>
    </div>

</div>
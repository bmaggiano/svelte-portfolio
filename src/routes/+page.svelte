<style>
    h1, h2, h3, h4, h5, h6, p, span, button, a {
        font-family: sans-serif;
    }
    h1 {
        font-size: 3rem;
        color: black;
    }
    a {
        margin-left: 1rem;
        color: white;
    }
    h2 {
        font-size: 1.2rem;
    }
    h3 {
        text-align: center;
        padding-top: 1rem;
        font-size: 2rem;
    }
    span {
        font-style: italic;
        color: rgb(104, 104, 104);
    }
    .header {
        display: flex;
        flex-direction: row;
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
        width: 40rem;
    }
    .title {
        padding-left: 2rem;
    }
    .subheader {
        background-color: rgb(255, 60, 0);
        color: white;
        text-align: center;
        padding: .01rem;
    }
    .content {
        height: 100vh;
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
    button {
        background-color: rgb(255, 60, 0);
        padding: .8rem;
        border-radius: .5rem;
        border: none;
        color: white;
        font-size: large;
        cursor: pointer;
    }
    .description {
        margin-left: 5rem;
    }
    .description h4{
        font-size: 1.8rem;
    }
    .description p {
        font-size: 1.1rem;
    }
    .project1 {
        width: 15rem;
    }
</style>

<div class="header">
    <!-- <div class="left-side"> -->
        <!-- <h1>Brandon Maggiano</h1>
        <p>Full Stack Software Engineer</p>
        <span>Chandler, AZ</span> -->
    <!-- </div> -->
    <div class="right-side">
        <div class="title">
            <h1>Built using the power of <br/> Svelte</h1>
            <span>a fast growing font end framework</span>
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

    <h3>Check out some of my recent projects</h3>
    <br/>
    <br/>
    <br/>

    <div class="project-left">
        <img 
            class="project1"
            src="./project1.png"
            alt=""
            />
        <div class="description">
            <h4>IG Caption Generator</h4>
            <p>Using the power of ChatGPT and Replicate, you're able to get custom generated captions based off a number of pre set vibes.</p>
            <button>Visit Site</button>
        </div>
    </div>

    <div class="project-left">
        <div class="description">
            <h4>Super Showdown</h4>
            <p></p>
        </div>
        <img 
            src="./sveltelogo.png"
            alt=""
            />
    </div>
    
</div>

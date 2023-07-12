<style>
    h1, p {
        color: black;
        font-family: sans-serif;
    }
    span {
        font-family: sans-serif;
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
        margin: 2rem;
    }
    .title {
        padding-left: 2rem;
    }
</style>

<div class="header">
    <div class="left-side">
        <!-- <h1>Brandon Maggiano</h1>
        <p>Full Stack Software Engineer</p>
        <span>Chandler, AZ</span> -->
    </div>
    <div class="right-side">
        <img
        class="headshot"
        src="./sveltelogo.png"
        alt="Brandon Maggiano"
        />
        <div class="title">
            <h1>Built using the power of <br/> Svelte</h1>
            <span>a fast growing font end framework</span>
        </div>
    </div>
</div>

<script>
    import { Blockquote } from 'flowbite-svelte'
    import '../../styles.css'

    const projects = [
        {
            name: "Super-ShowDown",
            tech: "NextJs/Clerk/Prisma/OpenAI",
            github: "https://github.com/bmaggiano/Super-Showdown",
            deployedLink:"https://super-showdown.vercel.app/",
        },
        {
            name: "IG Caption Generator",
            tech: "NextJs/OpenAI/Replicate/UploadThing",
            github: "https://github.com/bmaggiano/instagram-caption-generator",
            deployedLink:"https://igcap.dev",
        },
    ]

  </script>


<div class="header">
    <div class="right-side">
        <div class="title">
            <h1>My Projects</h1><br/>
              
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
    <h2> Making a career change can be one of the most daunting desicions of a person's life...</h2>
</div>

<div class="projects">
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Tech</th>
                <th>GitHub</th>
                <th>Deployed Link</th>
            </tr>
        </thead>
        <tbody>
            {#each projects as project}
                <tr>
                    <td>{project.name}</td>
                    <td>{project.tech}</td>
                    <td><a href={project.github}>{project.github}</a></td>
                    <td><a href={project.deployedLink}>{project.deployedLink}</a></td>
                </tr>
            {/each}
        </tbody>
    </table>

</div>
<script>
    import { Blockquote } from 'flowbite-svelte'
    import '../../styles.css'

    const projects = [
        {
            name: "Super ShowDown",
            tech: "NextJs/Clerk/Prisma/OpenAI/Node",
            github: "https://github.com/bmaggiano/Super-Showdown",
            deployedLink:"https://super-showdown.vercel.app/",
        },
        {
            name: "IG Caption Generator",
            tech: "NextJs/OpenAI/Replicate/UploadThing",
            github: "https://github.com/bmaggiano/instagram-caption-generator",
            deployedLink:"https://igcap.dev",
        },
        {
            name: "The Casual's Caddie",
            tech: "React/GraphQL/Swiper/Node",
            github: "https://github.com/bmaggiano/The-Casuals-Caddie",
            deployedLink:"https://the-casuals-caddie.herokuapp.com/",
        },
        {
            name: "Brandon's Book Search",
            tech: "React/Mongo/Express/Node/JWT",
            github: "https://github.com/bmaggiano/Brandons-Book-Search",
            deployedLink:"https://brandons-book-search.herokuapp.com/",
        },
        {
            name: "Three Tabs Three Ways",
            tech: "React",
            github: "https://github.com/bmaggiano/three-tabs-three-ways",
            deployedLink:"https://three-tabs-three-ways.vercel.app/",
        },
        {
            name: "React Portfolio",
            tech: "React",
            github: "https://github.com/bmaggiano/react-portfolio",
            deployedLink:"https://bmaggiano.github.io/react-portfolio/",
        },
        {
            name: "Rankedify",
            tech: "Handlebars/Autocompleter/Express/MySQL/Sequelize",
            github: "https://github.com/bmaggiano/Rankedify",
            deployedLink:"https://bmaggiano-rankedify.herokuapp.com/",
        },
        {
            name: "Text Editor",
            tech: "PWA",
            github: "https://github.com/bmaggiano/Text-Editor-Pwa",
            deployedLink:"https://bmaggiano-jate.herokuapp.com/",
        },
    ];
    import HeadInfo from '../HeadInfo.svelte';
  </script>


<HeadInfo title="Portfolio Projects" />


<header class="header">
    <div class="right-side">
        <div class="title">
            <h1>My Projects</h1><br/>
              
              <Blockquote class="blockquote" size='xl'>
              Creating projects and collaborating with others is a<br/>very important step in becoming a great web developer!
              </Blockquote>
        </div>
        <img
        class="headshot"
        src="./sveltelogo.png"
        alt="Svelte logo"
        />
    </div>
</header>

<section class="subheader">
    <h2>Check out some of my projects below!</h2>
</section>


<section class="content">
    <div class="projects bg-gray-50">
        <table>
        <thead >
            <tr class="text-gray-600">
                <th>Name</th>
                <th>Tech</th>
                <th>GitHub Link</th>
                <th>Deployed Link</th>
            </tr>
        </thead>
        <tbody>
            {#each projects as project}
                <tr>
                    <td class="font-semibold">{project.name}</td>
                    <td>{project.tech}</td>
                    <td class="text-center"><a class="bg-gray-200 p-1 px-2 border border-gray-400 rounded-md" href={project.github}>Click</a></td>
                    <td class="text-center"><a class="bg-gray-200 p-1 px-2 border border-gray-400 rounded-md"href={project.deployedLink}>Click</a></td>
                </tr>
                {/each}
            </tbody>
        </table>
    </div>
</section>
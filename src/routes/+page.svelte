<script lang="ts">
    import Skill from "$lib/components/Skill.svelte";
</script>

<div class="page">
    <header class="flex flex-col justify-center items-center gap-2 header text-center w-full py-4 bg-slate-900">
        <div>
            <span class="text-2xl text-yellow-600">Hi 0/</span>
            <span class="text-lg">
                Júlio here
            </span>
        </div>
        <div class="h-24 w-24">
            <img 
                src="me_linkeding_profile_pic.jpeg"
                alt="" 
                class="rounded rounded-full"
            />
        </div>
        <div>
            I'm a
            <span class="text-yellow-600">
                Software Engineer
            </span>
            currently working at 
            <u class="text-yellow-600">
                @Superone
            </u>
        </div>
    </header>

    <main class="main">
        <section class="bg-slate-100 p-4">
            <div class="text-yellow-900 text-3xl text-center pb-2 mb-4 border-b-2">
                SKILLS
            </div>
            <div class="flex gap-4 flex-wrap justify-center">
                <Skill iconUrl={"icons/NodeJS-Dark.svg"} description="NodeJS" />
                <Skill iconUrl={"icons/GoLang.svg"} description="Golang" />
                <Skill iconUrl={"icons/MySQL-Dark.svg"} description="MySQL" />
                <Skill iconUrl={"icons/AWS-Dark.svg"} description="AWS" />
                <Skill iconUrl={"icons/Svelte.svg"} description="Svelte" />
                <Skill iconUrl={"icons/React-Dark.svg"} description="React" />
                <Skill iconUrl={"icons/TailwindCSS-Dark.svg"} description="TailwindCSS" />
                <Skill iconUrl={"icons/Linux-Dark.svg"} description="Linux" />
                <Skill iconUrl={"icons/Git.svg"} description="Git" />
            </div>           
        </section>
        <section class="bg-black p-4">
            <div class="text-slate-300 text-3xl text-center">
                EXPERIENCE
            </div>
        </section>
        <section class="bg-yellow-600 p-4">
            <div class="text-slate-800 text-3xl text-center">
                PROJECTS
            </div>
        </section>
        <section class="bg-slate-600 p-4">
            <div class="text-slate-800 text-3xl text-center">
                EDUCATION
            </div>
        </section>
        <!--
        <section>
            Projects
        </section>
        <section>
            Tech stuff
        </section>
        -->
    </main>
</div>

<style>
    .page {
        color: white;
    }
    .header {
    }
</style>

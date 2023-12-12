<script lang="ts">
    import Skill from "$lib/components/Skill.svelte";
	import TimeLine from "$lib/components/TimeLine.svelte";
</script>

<div class="desktop h-screen">
    <div class="top-bar bg-black text-white flex items-center justify-between text-xs py-1 px-4">
        <div>
            Activities
        </div>
        <div>
            {new Date()}
        </div>
        <div>
            en
        </div>
    </div>
    <main class="main bg-gradient-to-b from-cyan-600 to-blue-600 w-full h-full relative">
       <div class="flex bg-slate-800 rounded-xl p-4 absolute top-1/4 left-4">
            <div class="dock w-full flex flex-col items-center justify-evenly gap-2">
                <div class="w-10 h-10 bg-cyan-800 rounded-lg"></div>
                <div class="w-10 h-10 bg-cyan-700 rounded-lg"></div>
                <div class="w-10 h-10 bg-cyan-900 rounded-lg"></div>
            </div>
       </div>

       <div class="terminal-container absolute flex items-center w-full h-full justify-center">
            <div class="terminal bg-gray-900 w-96 h-64 rounded-lg">
                <div class="flex items-center justify-center bg-gray-700 w-full h-6 rounded-t-lg relative">
                    <span></span>
                    <span class="text-gray-400 text-xs">juliogsn@os</span>
                    <div class="flex gap-2 text-xs text-gray-400 absolute right-2">
                        <div>
                            _
                        </div>
                        <div>
                            []
                        </div>
                        <div>
                            x
                        </div>
                    </div>
                </div>
            </div>
       </div>
    </main>
</div>

<style>

</style>

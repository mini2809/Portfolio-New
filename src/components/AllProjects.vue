<template>
    <div class="flex sm:justify-between justify-center sm:py-20 py-10 items-center lg:flex-nowrap lg:flex-row">
        <div class="flex sm:justify-start justify-center sm:w-[20%] w-[50%] ">
            <div 
                class="flex items-start text-[10px] lg:text-base text-[#C6C6C6] flex-col justify-center font-sans ">
                <div class="text-left sm:text-base lg:text-xl font-bold text-white">YouTube Clone</div>
                <div class="">TechStack: ReactJs</div>
                <div class="sm:inline-flex sm:w-[100%] w-1/2">Built UI similar to YouTube music web app with carousel
                    displaying
                    various songs and albums.</div>
                <a href="https://mini2809.github.io/youtubemusic-clone/" target="_blank">
                    <button
                        class=" lg:text-sm my-4 px-2 text-[10px] lg:h-8 sm:text-base font-sans text-black bg-white rounded-lg flex items-center justify-center text-center">Live
                        Preview</button>
                </a>
            </div>

        </div>
        <div class="flex md:w-[50%] sm:w-[70%] w-[50%]">
            <img src="/img/mobileMacYT.png" alt="" >
        </div>
    </div>
</template>
<script>
const projects = [
    {
        "id": 1,
        "title": "YouTube Music Clone",
        "techStack": "ReactJs",
        "details": ">Built UI similar to YouTube music web app with carousel displaying various songs and albums.",
    }
]
export default {
    name: 'AllProjects',
    data() {
        return projects;
    }
}
</script>
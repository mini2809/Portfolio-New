<template>
    <div>
        <div v-for="project in this.projects" :key="project.id">
            <div class="text-white">{{ project.title }}</div>
        </div>
        <div class="flex justify-between py-20 items-center">
            <div class="w-2/5 flex justify-start">
                <div
                    class="flex items-start text-[10px] lg:text-base text-[#C6C6C6] flex-col justify-center font-sans w-3/5">
                    <div class="text-left sm:text-base lg:text-xl font-bold text-white">YouTube Clone</div>
                    <div class="text-">TechStack: ReactJs</div>
                    <div class="sm:inline-flex hidden">Built UI similar to YouTube music web app with carousel
                        displaying
                        various songs and albums.</div>
                    <button
                        class=" lg:text-sm my-4 px-2 text-[10px] lg:h-8 sm:text-base font-sans text-black bg-white rounded-lg flex items-center justify-center text-center">Live
                        Preview</button>
                </div>

            </div>
            <div class="w-3/5">
                <img src="/img/mobileMacYT.png" alt="">
            </div>
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
<template>
    <header>
        <div class="flex mx-10 lg:py-10 py-4 sm:py-8 justify-between flex-wrap">
            <div>
                <a href="/">
                    <h1 class="font-bold text-4xl font-sans text-white">M.</h1>
                </a>

            </div>
            <div class="flex justify-between gap-8">
                <div
                    class="flex lg:gap-8 gap-4 cursor-pointer items-center font-light text-sm lg:text-base sm:text-sm font-sans text-white">
                    <a href="/">
                        <span>Home</span>
                    </a>
                    <a href="/">
                        <span>Projects</span>
                    </a>
                    <a href="https://drive.google.com/file/d/1wv_I7fbqKp3Hf2il9W5YGMh9hV4ti2sa/view?usp=share_link"
                        target="_blank">
                        <span>Resume</span>
                    </a>



                </div>
                <a href="mailto:minijain928@gmail.com" target="_blank">
                    <button
                        class="font-normal lg:text-sm text-sm px-3 lg:h-10 m-auto sm:text-md font-sans text-black bg-white rounded-lg">Work
                        with me</button>
                </a>

            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: 'HeaderSection'
}
</script>
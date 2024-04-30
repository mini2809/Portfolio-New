<template>
    <header>
        <div class="flex mx-10 lg:py-10 py-4 sm:py-8 justify-between flex-wrap">
            <div>
                <h1 class="font-bold text-4xl font-sans text-white">M.</h1>
            </div>
            <div class="flex justify-between gap-8">
                <div class="flex lg:gap-8 gap-4 cursor-pointer items-center font-light text-sm lg:text-base sm:text-sm font-sans text-white">
                    <span>Home</span>
                    <span>Projects</span>
                    <span>Resume</span>
                </div>
                <button
                    class="font-normal lg:text-sm text-sm px-3 lg:h-10 m-auto sm:text-md font-sans text-black bg-white rounded-lg">Work
                    with me</button>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    name: 'HeaderSection'
}
</script>
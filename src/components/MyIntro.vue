<template>
    <div class="flex items-center flex-col justify-center pb-10 ">
        <div class="my-20 flex justify-between">
            <img src="img/my-image.png" class="w-5/12" />
            <div class="flex justify-end">
                <div class=" w-3/4 flex flex-col text-[#C6C6C6] font-sans">
                    <div class="font-light lg:text-4xl text-2xl">Meet Mini Jain</div>
                    <div >I'm web engineer passionate about crafting fast and scalable web apps. With a focus on
                        elegant
                        design and robust architecture, I bring your digital ideas to life with precision and
                        performance.
                        Let's build something extraordinary together!</div>
                </div>
            </div>
        </div>
        <div class="flex justify-between items-center flex-col gap-20">
            <div>
                <button
                    class="cursor-pointer font-bold lg:text-sm text-sm px-3 py-2  lg:h-10 m-auto sm:text-md font-sans text-black bg-white rounded-lg">Let's
                    Work together!
                </button>
            </div>
            <div class="flex items-center justify-center gap-4 ">
                <img src="/img/LinkedIn.png" height="20px" width="20px" class="cursor-pointer" />
                <img src="/img/github.png" height="20px" width="20px" class="cursor-pointer" />
                <img src="/img/insta.png" height="20px" width="20px" class="cursor-pointer" />
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'MyIntro'
}
</script>
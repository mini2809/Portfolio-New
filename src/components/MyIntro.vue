<template>
    <div class="flex items-center flex-col justify-center pb-10 ">
        <div class="my-20 flex lg:justify-between lg:flex-nowrap flex-wrap justify-center">
            <img src="img/my-image-2.jpg" class="w-2/3 lg:w-1/3 origin-bottom lg:-rotate-12 my-4 sm:my-0" />
            <div class="flex lg:justify-end justify-center">
                <div class=" w-3/4 flex flex-col text-[#C6C6C6] font-sans">
                    <div class="font-light lg:text-4xl text-2xl my-2">Meet Mini Jain</div>
                    <div>I'm web engineer passionate about crafting fast and scalable web apps. With a focus on
                        elegant
                        design and robust architecture, I bring your digital ideas to life with precision and
                        performance.
                        Let's build something extraordinary together!</div>
                </div>
            </div>
        </div>
        <div class="flex justify-between items-center flex-col gap-20">
            <div>
                <a href="mailto:minijain928@gmail.com" target="_blank">
                <button
                    class="cursor-pointer font-bold lg:text-sm text-sm px-3 py-2  lg:h-10 m-auto sm:text-md font-sans text-black bg-white rounded-lg">Let's
                    Work together!
                </button>
                </a>
            </div>
            <div class="flex items-center justify-center gap-4 ">
                <a href="https://www.linkedin.com/in/mini-jain928" target="_blank">
                    <img src="/img/LinkedIn.png" height="20px" width="20px" class="cursor-pointer" />
                </a>
                <a href="https://github.com/mini2809" target="_blank">
                    <img src="/img/github.png" height="20px" width="20px" class="cursor-pointer" />
                </a>
                <a href="https://leetcode.com/u/mini_928/" target="_blank">
                    <img src="/img/insta.png" height="20px" width="20px" class="cursor-pointer" />
                </a>

            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'MyIntro'
}
</script>
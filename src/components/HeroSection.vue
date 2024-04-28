<template>
  <div class="bg-gradient-to-b from-[#17002F] to-black h-screen w-screen" >
  <header>
  <div class="flex mx-10 py-10 sm:py-8 justify-between md:flex-wrap-reverse">
    <div>
      <h1 class="font-bold lg:text-4xl sm:text-4xl font-sans text-white">M.</h1>
    </div>
    <div class="flex justify-between gap-8">
      <div class="flex lg:gap-8  sm:gap-4 items-center">
        <span class="font-light lg:text-md  sm:text-sm font-sans text-white">Home</span>
        <span class="font-light lg:text-md sm:text-sm font-sans text-white">Projects</span>
        <span class="font-light lg:text-md sm:text-sm font-sans text-white ">Resume</span>
    </div>
      <button class="font-light lg:text-sm px-2 lg:h-10 m-auto sm:text-md font-sans text-black bg-white rounded-lg">Work with me</button>
    </div>
  </div>
</header>
<mainBody>
  <div class="mx-16 mt-10 ">
    <h1 class="lg:text-4xl text-[#C6C6C6] font-sans font-bold">Hello,I'm Mini!</h1>
    <div class="lg:text-4xl text-[#C6C6C6] font-sans font-bold flex">I make websites
      <div class="slidingVertical">
        <span class="bg-gradient-to-r from-[#9627FF] to-[#19F4DA] inline-block text-transparent bg-clip-text indent-2">beautiful</span>
        <span class="bg-gradient-to-r from-[#9627FF] to-[#19F4DA] inline-block text-transparent bg-clip-text indent-2">performant</span>
        <span class="bg-gradient-to-r from-[#9627FF] to-[#19F4DA] inline-block text-transparent bg-clip-text indent-2">faster</span>
      </div>
    </div>
  </div>
</mainBody>

</div>
</template>

<script>
export default {
  name: 'HeroSection',
}
</script>
<template>
  <div class="bg-gradient-to-b from-[#17002F] to-black">
    <HeaderSection />
    <div class="md:container px-8 mx-auto sm:px-20 lg:px-40">
      <HeroSection />
      <AllProjects />
      <MyIntro />
    </div>
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue';
import HeaderSection from './components/HeaderSection.vue';
import AllProjects from './components/AllProjects.vue';
import MyIntro from './components/MyIntro.vue';
export default {
  name: 'App',
  components: {
    HeroSection,
    HeaderSection,
    AllProjects,
    MyIntro,
  }
}
</script>

<template>
  <div class="home">
    <HeaderSection />
    <HeroSection />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSection from '@/components/HeaderSection.vue'
import HeroSection from '@/components/HeroSection.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderSection,
    HeroSection
  },
}
</script>

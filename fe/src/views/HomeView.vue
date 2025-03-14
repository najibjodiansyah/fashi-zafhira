<template>
  <div class="home">
    <HeaderSection />
    <HeroSection />
    <WomanBanner />
    <SocialMediaPhoto />
    <PartnerSection />
    <FooterSection />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSection from '@/components/HeaderSection.vue'
import HeroSection from '@/components/HeroSection.vue'
import WomanBanner from '@/components/WomanBanner.vue';
import SocialMediaPhoto from '@/components/SocialMediaSection.vue';
import PartnerSection from '@/components/PartnerSection.vue';
import FooterSection from '@/components/FooterSection.vue';

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    HeaderSection,
    HeroSection,
    WomanBanner,
    SocialMediaPhoto,
    PartnerSection,
    FooterSection
  },
}
</script>

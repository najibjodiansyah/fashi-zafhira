<template>
    <div class="product">
        <HeaderSection />
        <p>
            Product saya akan ada disini
        </p>
        <FooterSection />
    </div>
</template>

<script>
  // @ is an alias to /src
  // import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSection from '@/components/HeaderSection.vue'
import FooterSection from '@/components/FooterSection.vue';

export default {
name: 'ProductView',
components: {
    // HelloWorld
    HeaderSection,
    FooterSection
},
}
</script>

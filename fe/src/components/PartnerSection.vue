<template>
    <div class="partner-logo">
        <div class="container">
            <vueOwlCarousel class="logo-carousel" :items="5">
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-1.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-2.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-3.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-4.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logo-5.png" alt="" />
                    </div>
                </div>
            </vueOwlCarousel>
        </div>
    </div>
</template>

<script>
    import vueOwlCarousel from 'vue-owl-carousel';
    export default {
        name: 'PartnerSection',
        components: {
            vueOwlCarousel
        }
    }
</script>
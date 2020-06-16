<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <InstaShayna />
    <LogoShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomenBanner from '@/components/WomenBanner.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import LogoShayna from '@/components/LogoShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';
export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    InstaShayna,
    LogoShayna,
    FooterShayna
  }
};
</script>

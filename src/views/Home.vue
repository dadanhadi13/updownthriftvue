<template>
  <div class="home">
      <HeaderUDT/>
      <HeroUDT/>
      <BannerUDT/>
      <InstaUDT/>
      <PartnerLogoUDT/>
      <FooterUDT/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderUDT from '@/components/HeaderUDT.vue'
import HeroUDT from '@/components/HeroUDT.vue'
import BannerUDT from '@/components/BannerUDT.vue'
import InstaUDT from '@/components/InstaUDT.vue'
import PartnerLogoUDT from '@/components/PartnerLogoUDT.vue'
import FooterUDT from '@/components/FooterUDT.vue'


export default {
  name: 'Home',
  components: {
    HeaderUDT,
    HeroUDT,
    BannerUDT,
    InstaUDT,
    PartnerLogoUDT,
    FooterUDT
  }
}
</script>

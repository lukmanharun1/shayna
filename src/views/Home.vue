<template>
  <div class="home">
    <HeaderSayna />
    <HeroSayna />
    <WomenSayna />
    <InstaSayna />
    <PartnerSayna />
    <FooterSayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderSayna from "@/components/HeaderSayna.vue";
import HeroSayna from "@/components/HeroSayna";
import WomenSayna from "@/components/WomenSayna";
import InstaSayna from "@/components/InstaSayna";
import PartnerSayna from "@/components/PartnerSayna";
import FooterSayna from "@/components/FooterSayna";
export default {
  name: "Home",
  components: {
    HeaderSayna,
    HeroSayna,
    WomenSayna,
    InstaSayna,
    PartnerSayna,
    FooterSayna,
  },
};
</script>

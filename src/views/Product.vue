<template>
  <div class="home">
    <HeaderSayna />
    <p>product saya akan berada disini</p>
    <FooterSayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderSayna from "@/components/HeaderSayna.vue";
import FooterSayna from "@/components/FooterSayna";
export default {
  name: "product",
  components: {
    HeaderSayna,
    FooterSayna,
  },
};
</script>

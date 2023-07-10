<template>
  <header class="header">
    <div class="container">
      <HeaderNavbar></HeaderNavbar>
      <HeaderBanner></HeaderBanner>
    </div>
  </header>
</template>

<script>
import HeaderNavbar from "@/layout/HeaderNavbar.vue";
import HeaderBanner from "@/layout/HeaderBanner.vue";

export default {
  name: "HeaderVue",
  components: { HeaderBanner, HeaderNavbar },
};
</script>

<style scoped></style>

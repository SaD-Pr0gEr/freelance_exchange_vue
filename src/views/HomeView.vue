<template>
  <HeaderVue></HeaderVue>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderVue from "@/layout/HeaderVue.vue";

@Options({
  components: { HeaderVue },
})
export default class HomeView extends Vue {}
</script>

<style lang="scss">
@import "@/assets/scss/pages/home.scss";
</style>

<template>
  <HeaderVue></HeaderVue>
  <main class="main">
    <ActualWorks></ActualWorks>
    <TopFreelancers></TopFreelancers>
  </main>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderVue from "@/layout/HeaderVue.vue";
import ActualWorks from "@/layout/ActualWorks.vue";
import TopFreelancers from "@/layout/TopFreelancers.vue";

@Options({
  components: { TopFreelancers, ActualWorks, HeaderVue },
})
export default class HomeView extends Vue {}
</script>

<style lang="scss">
@import "@/assets/scss/pages/home.scss";
</style>

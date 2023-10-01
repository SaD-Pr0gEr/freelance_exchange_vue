<template>
  <HeaderVue></HeaderVue>
  <main class="main">
    <ActualWorks></ActualWorks>
    <TopFreelancers></TopFreelancers>
    <WorkSteps></WorkSteps>
  </main>
  <FooterVue></FooterVue>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderVue from "@/layout/HeaderVue.vue";
import ActualWorks from "@/layout/ActualWorks.vue";
import TopFreelancers from "@/layout/TopFreelancers.vue";
import WorkSteps from "@/layout/WorkSteps.vue";
import FooterVue from "@/layout/FooterVue.vue";

@Options({
  components: { FooterVue, WorkSteps, TopFreelancers, ActualWorks, HeaderVue },
})
export default class HomeView extends Vue {}
</script>

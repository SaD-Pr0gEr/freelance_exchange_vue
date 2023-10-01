<template>
  <HeaderVue></HeaderVue>
  <div class="main"></div>
  <FooterVue></FooterVue>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeaderVue from "@/layout/HeaderVue.vue";
import FooterVue from "@/layout/FooterVue.vue";

@Options({
  components: { FooterVue, HeaderVue },
})
export default class ExchangeView extends Vue {}
</script>

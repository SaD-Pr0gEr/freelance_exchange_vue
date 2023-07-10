<template>
  <div class="container actual-works">
    <h3>Актуальные ворки</h3>
    <div class="works">
      <ActualWorkCard></ActualWorkCard>
      <ActualWorkCard></ActualWorkCard>
      <ActualWorkCard></ActualWorkCard>
      <ActualWorkCard></ActualWorkCard>
      <ActualWorkCard></ActualWorkCard>
      <EmptyCard :text="'Смотреть все ворки'"></EmptyCard>
    </div>
  </div>
</template>

<script>
import ActualWorkCard from "@/components/card/ActualWorkCard.vue";
import EmptyCard from "@/components/card/EmptyCard.vue";

export default {
  name: "ActualWorks",
  components: { EmptyCard, ActualWorkCard },
};
</script>

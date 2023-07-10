<template>
  <div class="container top-freelancers">
    <h3>Топ фрилансеров</h3>
    <div class="freelancers">
      <TopFreelancer></TopFreelancer>
      <TopFreelancer></TopFreelancer>
      <TopFreelancer></TopFreelancer>
      <TopFreelancer></TopFreelancer>
      <TopFreelancer></TopFreelancer>
      <EmptyCard
        class="freelancer-card"
        :text="'Посмотреть всех ТОП фрилансеров'"
      ></EmptyCard>
    </div>
  </div>
</template>

<script>
import TopFreelancer from "@/components/card/TopFreelancer.vue";
import EmptyCard from "@/components/card/EmptyCard.vue";

export default {
  name: "TopFreelancers",
  components: { EmptyCard, TopFreelancer },
};
</script>

<template>
  <div class="actual-work-card freelancer-card">
    <div class="user">
      <img src="@/assets/img/user2.png" alt="user2" />
      <div class="user-info">
        <p>Марина Королёва</p>
        <p class="profession">Разработчик PHP</p>
        <p>Выполено проектов: 65</p>
        <p class="rate-stars">
          <font-awesome-icon class="active" :icon="['fas', 'star']" />
          <font-awesome-icon class="active" :icon="['fas', 'star']" />
          <font-awesome-icon class="active" :icon="['fas', 'star']" />
          <font-awesome-icon class="active" :icon="['fas', 'star']" />
          <font-awesome-icon :icon="['fas', 'star']" />
        </p>
      </div>
    </div>
    <p class="look-btn full-green-outline">Написать</p>
  </div>
</template>

<script>
export default {
  name: "TopFreelancer",
};
</script>

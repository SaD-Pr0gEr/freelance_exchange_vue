<template>
  <nav class="header-navbar">
    <img src="@/assets/img/logo.svg" alt="site logo" />
    <router-link class="header-link" to="#">Биржа</router-link>
    <router-link class="header-link" to="#">Ворки</router-link>
    <router-link class="header-link" to="#">Конкурсы</router-link>
    <router-link class="header-link" to="#">Создать ворк</router-link>
    <router-link class="header-link" to="#">Создать заказ</router-link>
    <div class="auth">
      <router-link class="header-link signup" to="#">Регистрация</router-link>
      <router-link class="header-link login" to="#">Войти</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: "HeaderNavbar",
};
</script>

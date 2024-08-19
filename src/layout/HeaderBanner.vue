<template>
  <div class="banner">
    <div class="left-side">
      <h1>Покупайте фриланс-услуги в <span>два клика</span></h1>
      <p>
        Ворк — единица работы продавца, которую можно купить как товар в товар в
        магазине
      </p>
      <HeaderSearch></HeaderSearch>
      <p>Выберите рубрику, чтобы начать</p>
      <div class="rubrics">
        <p class="rubric">Тексты и переводы</p>
        <p class="rubric">Разработка</p>
        <p class="rubric">Дизайн</p>
        <p class="rubric">Аудио, видео монтаж</p>
        <p class="rubric">SEO и оптимизация</p>
        <p class="rubric">Бизнес и жизнь</p>
        <p class="rubric">Соцсети и реклама</p>
        <p class="rubric full-orange-outline">Все категории</p>
      </div>
    </div>
    <div class="right-side">
      <div class="frame-1"></div>
      <figure class="frame-circle frame-2"></figure>
      <figure class="frame-circle frame-3"></figure>
      <img class="coin animate" src="@/assets/img/coin.svg" alt="coin" />
      <img class="stars animate" src="@/assets/img/stars.svg" alt="stars" />
      <img class="wave" src="@/assets/img/wave.svg" alt="wave" />
      <img class="dots animate" src="@/assets/img/dots.svg" alt="dots" />
    </div>
  </div>
</template>

<script>
import HeaderSearch from "@/components/button/HeaderSearch.vue";

export default {
  name: "HeaderBanner",
  components: { HeaderSearch },
};
</script>

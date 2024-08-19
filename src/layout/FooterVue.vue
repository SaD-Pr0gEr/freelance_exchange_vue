<template>
  <footer class="footer">
    <div class="footer-content container">
      <div class="footer-col">
        <h2>Топ категории</h2>
        <a href="#!" class="footer-link">Тексты и переводы</a>
        <a href="#!" class="footer-link">Разработка</a>
        <a href="#!" class="footer-link">Дизайн</a>
        <a href="#!" class="footer-link">Аудио, видео монтаж</a>
        <a href="#!" class="footer-link">Соцсети и реклама</a>
        <a href="#!" class="footer-link">Бизнес и жизнь</a>
        <a href="#!" class="footer-link">SEO и оптимизация</a>
      </div>
      <div class="footer-col">
        <h2>О Проекте</h2>
        <a href="#!" class="footer-link">О Нас</a>
        <a href="#!" class="footer-link">Как Это Работает</a>
        <a href="#!" class="footer-link">Политика Приватности</a>
        <a href="#!" class="footer-link">Правила Пользования </a>
        <a href="#!" class="footer-link">Пресса о нас</a>
      </div>
      <div class="footer-col">
        <h2>Поддержка</h2>
        <a href="#!" class="footer-link">Контакты</a>
        <a href="#!" class="footer-link">Политика Безопасности</a>
        <a href="#!" class="footer-link">FAQ</a>
      </div>
      <div class="footer-col">
        <h2>Follow</h2>
        <div class="socials">
          <a href="#!">
            <FacebookVue />
          </a>
          <a href="#!">
            <InstagramVue />
          </a>
          <a href="#!">
            <TwitterVue />
          </a>
          <a href="#!">
            <LinkedinVue />
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import FacebookVue from "@/components/svg/FacebookVue.vue";
import TwitterVue from "@/components/svg/TwitterVue.vue";
import InstagramVue from "@/components/svg/InstagramVue.vue";
import LinkedinVue from "@/components/svg/LinkedinVue.vue";

@Options({
  components: { LinkedinVue, InstagramVue, TwitterVue, FacebookVue },
})
export default class FooterVue extends Vue {}
</script>

<template>
  <div class="container">
    <div class="container-header">
      <h2>Как решать задачи на WorkTap?</h2>
      <p>Идеально подходит для бизнеса и частных лиц</p>
    </div>
    <div class="solves">
      <SolveItem
        :icon-path="require('@/assets/img/step1.svg')"
        :title="'Выберите услугу'"
        :description="
          'В супермаркете WorkTap представлен широкий выбор услуг от' +
          ' квалифицированных специалистов.'
        "
      ></SolveItem>
      <SolveItem
        :icon-path="require('@/assets/img/step2.svg')"
        :title="'Оплатите'"
        :description="
          'Деньги будут перечислены продавцу после того, ' +
          'как он выполнит работу, и вы её одобрите. '
        "
      ></SolveItem>
      <SolveItem
        :icon-path="require('@/assets/img/step3.svg')"
        :title="'Получите результат'"
        :description="
          'Наш супермаркет гарантирует вам возврат средств в полном ' +
          'объёме в случае невыполнения заказа.'
        "
      ></SolveItem>
    </div>
  </div>
</template>

<script>
import SolveItem from "@/components/card/SolveItem.vue";

export default {
  name: "WorkSteps",
  components: { SolveItem },
};
</script>

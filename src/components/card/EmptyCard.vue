<template>
  <div class="actual-work-card empty-card">
    <a href="#!">{{ text }}</a>
  </div>
</template>

<script>
export default {
  name: "EmptyCard",
  props: ["text"],
};
</script>

<template>
  <div>
    {{ getDate }}
  </div>
</template>

<script setup>
import { computed } from "vue";

const getDate = computed({
  get() {
    const date = new Date();
    const fullValue = (val) => (val > 9 ? val : `0${val}`);
    return `${fullValue(date.getDate())}.${fullValue(date.getMonth() + 1)}.${date.getFullYear()}`;
  },
});
</script>

<style scoped></style>

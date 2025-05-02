<template>
  <div>
    {{
      `${fullValue(date.getDate())}.${fullValue(date.getMonth())}.${date.getFullYear()}`
    }}
  </div>
</template>

<script setup>
const fullValue = (val) => (val > 9 ? val : `0${val}`);
const date = new Date();
</script>

<style scoped></style>

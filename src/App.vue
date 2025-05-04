<script setup>
import Button from "./components/Button.vue";
</script>
<template>
  <main class="main">
    <Button> Начать игру </Button>
  </main>
</template>

<script setup></script>

<style scoped>
.main {
  display: grid;
  place-items: center;
  min-height: 100vh;
  font-family: "Montserrat", sans-serif;
  font-style: normal;
  background-color: var(--bg-main);
}
</style>

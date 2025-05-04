<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>
<style scoped>
.btn {
  max-width: 335px;
  min-width: 335px;
  max-height: 68px;
  min-height: 68px;
  background-color: var(--bg-btn);
  color: var(--font-btn);
  font-size: 24px;
  line-height: 36px;
  font-weight: 400;
  border: none;
  border-radius: 100px;
}
</style>

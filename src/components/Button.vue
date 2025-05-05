<template>
  <button class="btn">
    <slot></slot>
  </button>
</template>
<style scoped>
.btn {
  max-width: var(--width-btn);
  min-width: var(--width-btn);
  max-height: var(--height-btn);
  min-height: var(--height-btn);
  background-color: var(--bg-btn);
  color: var(--color-white);
  font-size: var(--font-size-btn);
  line-height: var(--line-height-btn);
  font-weight: var(--font-weight-btn);
  border: var(--border-btn);
  border-radius: var(--border-radius-btn);
  cursor: var(--cursor-btn);
}
.btn:hover {
  background-color: var(--bg-btn-hover);
}
</style>

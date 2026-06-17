<script setup lang="ts"></script>

<template>
  <section class="baseCard">
    <slot />
  </section>
</template>

<style scoped lang="scss">
.baseCard {
  background-color: #011f35;
  border-radius: 16px;
  padding: 20px 32px;
  display: flex;
  flex-direction: column;
  gap: 20px;
  overflow: hidden;
  width: 100%;
}
</style>

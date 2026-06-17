<script setup lang="ts">
import BaseCard from '@/components/BaseCard.vue'
import { ref } from 'vue'
</script>

<template>
  <div class="container">
    <header>The Magnificent Seven Companies</header>

    <div class="carousel">
      <BaseCard class=""></BaseCard><BaseCard class=""></BaseCard><BaseCard class=""></BaseCard
      ><BaseCard class=""></BaseCard><BaseCard class=""></BaseCard><BaseCard class=""></BaseCard
      ><BaseCard class=""></BaseCard>
    </div>
    <div class="wrapper">
      <BaseCard>Revenue last 3 years</BaseCard
      ><BaseCard>Revenue Breakdown Magnificent Seven</BaseCard>
    </div>
    <div class="wrapper">
      <BaseCard>Net Income TTM</BaseCard><BaseCard>Gross Margin in % LQ</BaseCard
      ><BaseCard>Revenue Growth in % YoY </BaseCard>
    </div>
  </div>
</template>

<style>
html,
body {
  margin: 0;
  padding: 0;
  color: #ffffff;
  box-sizing: border-box;
}
#app {
  background: radial-gradient(71.11% 100% at 50% 0%, #020204 14.6%, #011f35 100%);
  min-height: 100vh;
  align-items: center;
  display: flex;
  justify-content: center;
}
.container {
  height: 100vh;
  max-width: 1440px;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 32px;
}
.carousel {
  background-color: #023a6233;
  border-radius: 20px;
  padding: 24px;
  gap: 24px;
  display: flex;
  flex-direction: row;
}
.wrapper {
  display: flex;
  justify-content: space-between;
  width: 100%;
  gap: 32px;
}
header {
  width: 100%;
}
</style>

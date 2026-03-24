<script setup>
import { ref } from "vue";

const activeIndex = ref(0);

const items = ref([
  { id: 1, name: "Главная" },
  { id: 2, name: "Проект" },
  { id: 3, name: "Команда" },
  { id: 4, name: "Достижения" },
  { id: 5, name: "Проекты" },
]);
</script>

<template>
  <header class="container">
    <p
      v-for="(item, index) in items"
      :key="item.id"
      class="item"
      :class="{ active: activeIndex === index }"
      @click="activeIndex = index"
    >
      {{ item.name }}
    </p>
  </header>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  position: relative;
  z-index: 100;
}

.item {
  color: var(--text);
  font-size: 30px;
  cursor: pointer;
  font-family: var(--sans);
}

.active {
  background-color: var(--bg-active);
  color: var(--text-span);
  text-align: center;
  padding: 15px 61px;
  border-radius: 34px;
}
</style>

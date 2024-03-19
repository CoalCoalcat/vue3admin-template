<script setup lang="ts"></script>

<template>
  <div id="app">
    <img class="logo" src="./assets/logo.png" alt="Vue logo" />
    <img class="logo vue" src="./assets/vue.png" alt="Vue logo" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

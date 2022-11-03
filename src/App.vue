<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div>
    <h1>oi</h1>
  </div>
  <RouterView />
</template>

<style scoped>

</style> -->


<template>
  <div id="app">
    <RouterView />
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<style lang="scss">
body,
html {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
  overflow-x: hidden;
}

/* ===== Scrollbar CSS ===== */
/* Firefox */
* {
  scrollbar-width: auto;
  scrollbar-color: rgba(123, 123, 123) rgba(255, 255, 255, 0.05);
}

/* Chrome, Edge, and Safari */
*::-webkit-scrollbar {
  width: 5px;
}

*::-webkit-scrollbar-track {
  background: rgba(255, 255, 255, 0.05);
}

*::-webkit-scrollbar-thumb {
  background-color: rgba(123, 123, 123);
  border-radius: 10px;
  border: 2px none #ffffff;
}

ul {
  margin: 0 !important;
  padding: 0 !important;
}
</style>
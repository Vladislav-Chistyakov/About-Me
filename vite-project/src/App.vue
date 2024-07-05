<script setup>
import Main from "./components/Main/index.vue";
import Profile from "./components/Profile/index.vue";
</script>

<template>
  <div class="app">
    <Profile />
    <Main />
  </div>
</template>

<style scoped>
.app {
  display: flex;
  flex-direction: row;
}
</style>

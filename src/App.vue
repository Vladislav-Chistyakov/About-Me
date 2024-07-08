<script setup>
import Main from "./components/Main/index.vue";
import Profile from "./components/Profile/index.vue";
</script>

<template>
  <div class="container">
    <Profile />
    <Main />
  </div>
</template>

<style scoped>
@media screen and (min-width: 576px){}
@media screen and (min-width: 768px){}
@media screen and (min-width: 1024px){}
@media screen and (min-width: 1440px){}
@media screen and (min-width: 1600px){}
@media screen and (min-width: 1920px){}

.container {
  display: flex;
  flex-direction: column;

  @media screen and (min-width: 1024px){
    flex-direction: row;
  }

  @media screen and (min-width: 1920px){
    margin: 0 auto;
    max-width: 1920px;
  }
}

</style>

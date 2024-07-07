<script setup>
import Main from "./components/Main/index.vue";
import Profile from "./components/Profile/index.vue";
</script>

<template>
  <div class="app">
    <div class="main">
      <Profile />
    </div>
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

.app {
  display: flex;
  flex-direction: column;
  .main {
    display: none;
  }
  @media screen and (min-width: 576px){

  }

  @media screen and (min-width: 768px){}

  @media screen and (min-width: 1024px){
    flex-direction: row;
  }

  @media screen and (min-width: 1440px){}

  @media screen and (min-width: 1600px){}

  @media screen and (min-width: 1920px){}

}

</style>

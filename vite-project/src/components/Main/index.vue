<script>
export default {
  name: "index",
  data () {
    return {
      text: '11111'
    }
  },
  computed: {
    test () {
      return 'test 111123123123123' + this.text
    }
  }
}
</script>

<template>
  <div class="main-block">
    <div class="main-block__wrapper"></div>
  </div>
</template>

<style scoped>

</style>

<template>
  <div id="app">
    <router-view></router-view>
    <footer-bar></footer-bar>
  </div>
</template>

<script>
  import FooterBar from '@/components/FooterBar.vue'
  export default {
    components: {
      FooterBar
    }
  }
</script>
<style lang="scss">

</style>

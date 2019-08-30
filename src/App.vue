<template>
  <div id="app">
    <router-link to="/msite">测试</router-link>
    <router-view></router-view>
    <FooterGuide></FooterGuide>
  </div>
</template>
<script>
  import FooterGuide from './components/FooterGuide/FooterGuide.vue'
  import Msite from './pages/Msite/Msite'
  export default {
    name:'App',
    components: {
      FooterGuide,
      Msite
    }
  }
</script>
<style lang="stylus" rel="stylesheet/stylus">
  #app
    width 100%
    height 100%
    background #f5f5f5
</style>

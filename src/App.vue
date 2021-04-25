<template>
  <div id="app">
    <m-header></m-header>
    hello world
    <router-view/>
  </div>
</template>

<script>
import MHeader from "src/components/m-header/m-header";
export default {
  components:{
    MHeader
  },
  name: 'App'
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~common/stylus/variable"
#app
  color: #2c3e50
</style>

<template>
  <div id="app">
    <m-header></m-header>
    <tab />
    <router-view />
  </div>
</template>

<script>
import MHeader from 'src/components/m-header/m-header'
import Tab from 'src/components/tab/tab'
export default {
  components: {
    MHeader,
    Tab
  },
  name: 'App'
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~common/stylus/variable"
</style>

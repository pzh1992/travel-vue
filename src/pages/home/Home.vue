<template>
  <div>
    <home-header class='header'>

    </home-header>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
export default{
  name: 'Home',
  components: {
    HomeHeader
  }
}
</script>

<style lang='stylus' scoped>
  .header
    height: .86rem
    .header-left
      width: .64rem
      float: left
    .header-input
      flex: 1
    .header-right
      width: 1.24rem
      float: tight
</style>

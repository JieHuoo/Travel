<template>
  <div>
    <home-header></home-header>
    <home-swipter></home-swipter>
    <home-icons></home-icons>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwipter from './components/Swiper'
import HomeIcons from './components/Icons'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwipter,
    HomeIcons
  }
}
</script>

<style>

</style>

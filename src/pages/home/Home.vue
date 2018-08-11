<template>
  <div>
    <home-header></home-header>
    <home-swipter></home-swipter>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwipter from './components/Swiper'
export default {
  name: 'Home',
  components: {
    HomeHeader,
    HomeSwipter
  }
}
</script>

<style>

</style>

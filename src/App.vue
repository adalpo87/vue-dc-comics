<template>
  <div id="app">
    <HeaderDC />
    <MainDC />
    <FooterDC />
  </div>
</template>

<script>
import HeaderDC from './components/HeaderDC.vue'
import MainDC from './components/MainDC.vue'
import FooterDC from './components/FooterDC.vue'

export default {
  name: 'App',
  components: {
    FooterDC,
    HeaderDC,
    MainDC,
  }
}
</script>

<style lang="scss">
 *{
   margin: 0;
   padding: 0;
   box-sizing: border-box;
 }
 body{
   font-family: 'Roboto', sans-serif;
 }
</style>

<template>
  <main>
      <div class="wrapper">
          <div class="container">
              <span class="cur-series">
                  CURRENT SERIES
              </span>
          </div>
      </div>
      <div class="series">
          
              <ul>
                  <MainCard 
                   v-for="(comic, index) in comics" :key="index"
                   :hero="comic"
                   />
              </ul>
            <button>LOAD MORE</button>
      </div>
      
  </main>
</template>

<script>
import comics from '@/assets/data/dc-comics.js'
import MainCard from '@/components/MainCard.vue'

export default {
    name: 'MainDC',
    data(){
          return{
                comics
          }
    },
    components: {
          MainCard,
    }
}
</script>

<style lang="scss" scoped>
    @import '../assets/style/vars.scss';
    @import '../assets/style/main-wrapper.scss';
     @import '../assets/style/main-series.scss';
</style>
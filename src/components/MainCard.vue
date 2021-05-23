<template>
  
    <li>
        <div class="img-dc">
            <img :src="hero.thumb" :alt="hero.type">
        </div>
        <a href="">{{hero.series}}</a>
        
    </li>

</template>

<script>
export default {
    name: "MainCard",
    props: {
        hero: Object
    }
    }

</script>

<style lang="scss" scoped>
    @import '../assets/style/vars.scss';
    @import '../assets/style/main-series.scss';
</style>
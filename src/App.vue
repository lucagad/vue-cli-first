<template>
  <div id="app">
    <TitleComp />
    <HeroComp />
  </div>
</template>

<script>

import TitleComp from './components/TitleComp.vue'
import HeroComp from './components/HeroComp.vue'


export default {
  name: 'App',
  components: {
    TitleComp,
    HeroComp
  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
}

</style>

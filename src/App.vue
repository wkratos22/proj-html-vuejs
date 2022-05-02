<template>
  <div id="app">
    <headerComp/>
    <headerComp1/>
    <MainComp/>
    <MainComp1/>
    <FooterComp/>
    
  </div>
</template>

<script>
import "bootstrap"
import headerComp from './components/headerComp.vue'
import headerComp1 from './components/headerComp1.vue'
import MainComp from './components/MainComp.vue'
import MainComp1 from './components/MainComp1.vue'
import FooterComp from './components/FooterComp.vue'

export default {
  name: 'App',
  components: {
    headerComp,
    headerComp1,
    MainComp,
    MainComp1,
    FooterComp,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  cursor: default;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
@import "bootstrap/dist/css/bootstrap.min.css";
</style>

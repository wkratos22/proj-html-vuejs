<template>
  <div id="app">
    <headerComp/>
    <headerComp1/>
    
  </div>
</template>

<script>
import "bootstrap"
import headerComp from './components/headerComp.vue'
import headerComp1 from './components/headerComp1.vue'

export default {
  name: 'App',
  components: {
    headerComp,
    headerComp1
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
@import "bootstrap/dist/css/bootstrap.min.css";
</style>

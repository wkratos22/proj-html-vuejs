<template>
  <div class="head-bg-color">
    <div class="container space">
      <div class="mt-3">
        <font-awesome-icon class="px-3" icon="fa-solid fa-phone" />
        <p class="inline">Call us for a free Quote: 1.800.555.6789</p>
      </div>
      <div class="inline mt-3">
        <font-awesome-icon class="px-2" icon="fa-brands fa-twitter" />
        <font-awesome-icon class="px-2" icon="fa-brands fa-facebook" />
        <font-awesome-icon class="px-2" icon="fa-brands fa-instagram" />
        <font-awesome-icon class="px-2" icon="fa-brands fa-youtube" />
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'headerComp',
    
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .inline {
    display: inline-block;
  }

  .head-bg-color {
    background-color: #69bf14;
    color: white;
    text-align: center;
  }

  .space{
    display: flex;
    justify-content: space-between;
  }
</style>
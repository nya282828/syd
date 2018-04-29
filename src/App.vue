<template>
  <div id="app">
    <!-- <router-view/> -->
    <div class="sample">
      <p class="sample__text">Hellow World</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.sample {
  width: 100%;
  max-width: 640px;
  margin: 0 auto;

  &__text {
    font-size: 32px;
    text-align: center;
  }
}
</style>

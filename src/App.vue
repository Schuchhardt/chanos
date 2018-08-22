<template>
  <div id="app">
    <h1>Chanos</h1>
    <div class="gif">
    </div>
    <h1>Everywhere</h1>
  </div>
    <!-- <router-view/> -->
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.gif{
  height: 100vh;
  background-image: url('https://media3.giphy.com/media/K34FVrUx8ggyA/giphy.gif');
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}
@media(min-width: 767px){
  .gif{
    width: 50vw;
    margin: auto;
    display: block;
  }
}
</style>

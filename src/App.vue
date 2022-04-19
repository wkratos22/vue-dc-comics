<template>
  <div class="container">
    <img class="logo" alt="Vue logo" src="./assets/dc-logo.png">

    <div class="nav-bar">
      <navBar id="app"/>
    </div>

    <div>
      <comics/>
    </div>

    <div>
      <blueBar/>
    </div>
    <div class="bg-image">
      <primoFooter/>
    </div>
  </div>
</template>

<script>
import navBar from './components/navBar.vue'
// import ContentHere from './components/contentHere.vue'
import blueBar from './components/blueBar.vue'
import primoFooter from './components/primoFooter.vue'
import comics from './components/comics.vue'

export default {
  name: 'App',
  components: {
    navBar,
    // ContentHere,
    blueBar,
    primoFooter,
    comics,
  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: grey;
}

.logo{
  padding: 20px;
}

.nav-bar{
  margin-top:0;
  float: right;
  margin-top: 1.3%;
}

.bg-image{
  background-image: url(./assets/footer-bg.jpg);
  height: 420px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  max-width: 100%;
}
</style>

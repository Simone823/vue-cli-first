<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle/>
    <MyHero/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import MyHero from './components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #2c3e50;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#app img {
  filter: drop-shadow(0 0 10px red);
}
</style>

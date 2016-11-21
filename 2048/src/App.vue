<template>
  <div id="app">
    <img src="./assets/logo.png">
    <a href="http://codepen.io/camsong/pen/wcKrg">2048</a>
    <hello></hello>
    <div> git commit -m "Add 2048"</div>
    <div>git push -u origin master</div>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style lang="scss">
$field-width: 500px;
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

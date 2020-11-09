<template>
  <div id="app">
    <div class="header">
      <div class="header" id="logo">
        <img src="./assets/images/logo.svg" alt="logo">
      </div>
      <Menu />
    </div>
    <Home />
  </div>
</template>

<script>
  import Home from './components/Home.vue'
  import Menu from './components/Menu.vue'

export default {
  name: 'App',
  components: {
    Home,
    Menu
  }
}
</script>

<style>
  body {
    margin: 0;
  }

  #app {
    height: 100vh;
    background: #C4C4C4;
  }

  .header {
    height: 100px;
    background: #D0773C;
  }

  #logo {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    position: absolute;
    left: 30px;
    width: 161px;
    height: 161px;
    border-radius: 50%;
  }

  #logo img {
    width: 110px;
    height: 115px;
  }




</style>

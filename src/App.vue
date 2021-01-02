<template>
  <div id="app">
    <div class="container">
<Header />
    <router-view/>
    </div>
    
  </div>
</template>

<script>
import Header from './components/layout/Header';
export default {
  name: "app",
  components: {
    Header
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #42b983;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.container {
    max-width: 1100px;
    margin: auto;
    overflow: auto;
    padding: 0 2rem;
}
body {
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
    background: #e8f7f0;

}
</style>

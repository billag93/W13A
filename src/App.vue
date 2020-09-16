<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>

import pageHeader from "./components/header.vue"
import pageFooter from "./components/footer.vue"
import pageBody from "./components/body.vue"


export default {
  name: 'App',
  components: {
    pageHeader,
    pageFooter,
    pageBody
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
  margin-top: 60px;
}
</style>

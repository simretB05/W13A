<template>
  <div id="app">
  <page-header/>
  <page-body/>
  <page-footer/>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import PageBody from './components/pageBody.vue';
import PageFooter from './components/PageFooter.vue'
export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageFooter
    

  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
body{
  
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

  
}
</style>

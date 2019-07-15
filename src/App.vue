<template>
  <div id="app">
    <el-container>
      <Header></Header>
      <!-- <router-view></router-view> -->
    </el-container>
  </div>
</template>

<script>
import Header from '@/views/Header'
export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
html,body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

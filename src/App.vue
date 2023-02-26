<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
  <TemplateSyntax/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TemplateSyntax from './components/TemplateSyntax.vue'
//目前进度
// https://www.bilibili.com/video/BV1QA4y1d7xf?p=7&vd_source=b3b090d94cf21e58e86824532f45ccdd

export default {
  name: 'App',
  components: {
    TemplateSyntax
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

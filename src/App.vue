<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  created () {
    console.log('I was born here')
  },
  beforeCreate () {
    console.log('before Created')
  },
  beforeDestroy () {
    console.log('This is my last word')
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Do+Hyeon');
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  font-family: 'Do Hyeon', sans-serif;
  font-size: 40px;
}
</style>

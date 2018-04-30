<template>
  <div id="app">
    <div class="HEAD"> THIS IS App.vue </div>
    <my-title :titleName="title"></my-title>
    <button @click="myFuncl3lcS"> Alert </button>
  </div>
</template>

<script>
import myTitle from './components/HelloWorld'
export default {
  name: 'App',
  components: { myTitle },
  data () {
    return {
      title: 'princel3lcS'
    }
  },
  created () {
    console.log('I was born here')
  },
  beforeCreate () {
    console.log('before Created')
  },
  beforeDestroy () {
    console.log('This is my last word')
  },
  methods: {
    myFuncl3lcS () {
      alert('Hello l3lcS')
    }
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
.HEAD{
  font-family: 'Do Hyeon', sans-serif;
  font-size: 90px;
}
</style>

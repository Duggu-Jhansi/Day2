<template>
  <h1>{{title }}</h1>
  <ModalComponents/>
 
</template>

<script>

import ModalComponents from './components/ModalComponents.vue';

export default {
  name: 'App',
  components:{ModalComponents },
  data(){
    return{
      title:"My First Vue Form"
    }
  },
  
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

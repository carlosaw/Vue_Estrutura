<script>
import Teste from './Teste.vue';

export default {
  data() {
    return {
      msg:'Olá Mundo!'
    }
  },
  components:{
    Teste
  }
}
</script>

<template>
  <div id="app">
    <h1>{{msg}}</h1>
    <teste />
  </div>
</template>

<style>
h1 {
  background-color: #FF0000;
  color: #FFFFFF;
}
</style>
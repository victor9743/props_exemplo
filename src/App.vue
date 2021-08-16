<template>
  <div>
    <comp1 :nome="Nnome" :numero="Nnumero" email="teste@teste"/>
    <comp1 nome="hello wolrd 2" numero=2 email="teste@teste2"/>
    <comp1 nome="hello wolrd 3" numero=3 email="teste@teste3"/>

  </div>
</template>

<script>

import comp1 from './components/comp1.vue'
// import comp2 from './components/comp2.vue'

export default {
  name: 'App',
  components: {
    comp1,
    
  },
  data(){
    return{

      Nnome: 'Hello Wolrd',
      Nnumero: 112312
      
    }
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

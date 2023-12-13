<template>
    <div>
      <h1>App component</h1>
      <input type="text" placeholder="n..." v-model="msg">
      <Products :greetings="msg"/>
    </div>
</template>

<script>
import Products from './components/Products.vue';

export default {
  data(){
    return{
      msg : '',
    }
  },
  name: 'App',
  components: {
    Products,
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

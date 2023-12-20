<template>
  <div id="app">
    <h1>Calculadora</h1>
    <MyCalculatorVue />
  </div>
</template>

<script>
import MyCalculatorVue from './main/MyCalculator.vue';

export default {
  components: { MyCalculatorVue }
}
</script>

<style>
* {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>

<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <div>
      <h4 class="red" :style="fontStyle">{{ products[1] }}</h4>
      <p>{{ prices[1] }} dollors</p>
    </div>
    <div>
      <h4>{{ products[2] }}</h4>
      <p>{{ prices[2] }} dollors</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      prices: ["100", "200", "300"],
      fontStyle: "color : purple",
      products: ["mama", "lala", "baba"],
    };
  },
  components: {},
};
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

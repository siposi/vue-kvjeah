<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Welcome To The Test Ground" />
    <RawRegItem msg="TvT 哈哈哈 T^T" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import RawRegItem from './components/RawRegItem.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    RawRegItem,
  },
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

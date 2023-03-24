<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" width="100" />
    <HelloWorld msg="Welcome To" />
    <HelloWorld msgDetail="ViApp" />
    <ViButton judul="PT. AAA" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ViButton from './components/ViButton.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    ViButton,
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

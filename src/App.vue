<template>
  <div id="app">
    <Hello msg="Hello Vue" />
  </div>
</template>

<script>
import Hello from './components/Hello.vue';

export default {
  name: 'App',
  components: {
    Hello,
  },
};
</script>

<style>
#app {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

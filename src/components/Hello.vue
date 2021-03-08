<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h1 {
  color: #2c3e50;
}
</style>

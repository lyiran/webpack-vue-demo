<template>
  <div>
    <input type="text" v-model="message"/>
    {{ message }}
  </div>
</template>
<script>
  module.exports = {
    data() {
      return {
        message: 'hello'
      };
    },

    mounted() {
      console.log('mounted');
    }
  }
</script>
<style>
  div {
    color: red;
  }
</style>

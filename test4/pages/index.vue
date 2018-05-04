<template lang="pug">
  h1.h1(@click="show") HELLO WORLD
</template>

<script lang="babel">
  import AppLogo from '~/components/AppLogo.vue'

  export default {
    components: {
      AppLogo
    },
    created(){

      console.clear();
    },
    methods: {
      show() {
        alert('name');
      }
      
    }
  }
</script>

<style lang="sass">
  .h1 
    color: red
</style>
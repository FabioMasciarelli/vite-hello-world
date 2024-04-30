<script>
  import AppTitle from './components/AppTitle.vue'

  export default {
    components: {
      AppTitle
    },
    data() {
      return {

      }
    }
  }
</script>

<template>

  <div>
    <AppTitle/>

  </div>


</template>

<style>
  div {
    background-color: blue;
    height: 100%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>

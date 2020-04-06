<template>
  <div id="app">
    <navbar/>
    
    <b-container class="my-4">
      <card-wrapper/>
    </b-container>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import CardWrapper from './components/CardWrapper.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    CardWrapper
  }
}
</script>

<style>
body {
  background-color: rgb(248, 248, 252);
}
</style>

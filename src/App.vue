<template>
  <div class="container-fluid m-0 p-0">
    <nav-bar/>
    <router-view/>    
  </div>
</template>

<script>
import NavBar from "./components/layout/NavBar"
export default {
  components: {
    NavBar
  }
}
</script>

<style>

</style>

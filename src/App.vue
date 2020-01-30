<template>
  <div id="app">
    <nav-section />
    <router-view />
  </div>
</template>

<script>
  import NavSection from "@/components/Navbar";
  
  export default {
    components: {
      NavSection,
    }
  }
</script>

<style lang="scss">
  #app {
    font-family: "Avenir", Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    padding: 0;
    margin: 0;
  }

  body{
    margin: 0;
    padding: 0;
  }
</style>

<template>
  <header>
    <div id="nav">
      <h1></h1>
      <router-link to="/">Home<font-awesome-icon icon="home"/></router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/works">Works</router-link> |
      <router-link to="/contact">Contact</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "NavHeader"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss"></style>
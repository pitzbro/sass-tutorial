<template>
  <div class="home">
    <header>
      <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
      </div>
      <img class="logo" alt="SASS logo" src="../assets/logo.svg" />
    </header>
    <HelloWorld msg="Welcome to Your SASS Tutorial!" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>

<style scoped lang="scss">
@import "../styles/views/home-page.scss";
// #nav {
//   background-color: $clr4;
// }
</style>

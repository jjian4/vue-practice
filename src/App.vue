<template>
  <div id="app">
    <AppHeader />
    <Home />
    <Admin />
  </div>
</template>

<script>
import AppHeader from "./components/Header";
import Home from "./components/Home";
// import Menu from "./components/Menu";
import Admin from "./components/Admin";

export default {
  name: "App",
  components: {
    AppHeader,
    Home,
    // Menu,
    Admin,
  },
};
</script>

<style>
</style>

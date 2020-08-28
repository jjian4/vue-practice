<template>
  <div id="app">
    <AppHeader />
    <Home />
    <Menu />
  </div>
</template>

<script>
import AppHeader from "./components/Header";
import Home from "./components/Home";
import Menu from "./components/Menu";

export default {
  name: "App",
  components: {
    AppHeader,
    Home,
    Menu,
  },
};
</script>

<style>
</style>

<template>
  <header>
    <div class="header_logo">
      <img src="../assets/images/planet.png" alt="pizza planet" />
      <h1 href="/">PIZZA PLANET</h1>
    </div>
    <nav>
      <ul>
        <!-- Equivalent to to="/" (without colon or variable) -->
        <router-link :to="{name: 'homeLink'}" tag="li">
          <a>Home</a>
        </router-link>
        <span>~</span>
        <router-link :to="{name: 'menuLink'}" tag="li">
          <a>Menu</a>
        </router-link>
        <span>~</span>
        <router-link :to="{name: 'contactLink'}" tag="li">
          <a>Contact</a>
        </router-link>
        <span>~</span>
        <router-link :to="{name: 'aboutLink'}" tag="li">
          <a>About Us</a>
        </router-link>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "appHeader",
};
</script>

<style scoped>
h1 {
  font-size: 1.3em;
}

.header_logo {
  background-image: linear-gradient(
    45deg,
    #d85226 25%,
    #f79e28 25% 50%,
    #d85226 50% 75%,
    #f79e28 75% 100%
  );
  background-size: 80px 80px;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 10px;
}

.header_logo img {
  max-width: 25vw;
}

ul {
  padding: 10px 0;
}

li {
  display: inline-block;
}

@media screen and (min-width: 900px) {
  .header_logo img {
    max-width: 20vw;
  }
}
</style>

<template>
  <nav class="d-flex justify-content-between">
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    <img src="../src/assets/logoNavbar.png" />
    <div class="me-5">
      <button type="button" class="btn text-white fw-bold me-3">Login</button>
      <button class="btn btn-pink text-white fw-bold">Register</button>
    </div>
  </nav>
  <router-view />
  <!-- <div>

  </div> -->
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  background-color: black;
  padding: 1rem;
}

/* nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */

.btn-pink {
  background-color: #CD2E71 !important;
}
</style>

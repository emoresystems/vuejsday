<template>
  <div>
    <nav>
      <router-link to="/">Homee</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/services">Services</router-link>
    </nav>
    <router-view />

    <footer>
      <p>footer</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

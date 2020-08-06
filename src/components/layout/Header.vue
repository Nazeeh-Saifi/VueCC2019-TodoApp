<template>
  <header class="header">
    <h1>TODO LIST:</h1>
    <div class="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>


<style scoped>
.header {
  background: #333;
  color: #ffffff;
  text-align: center;
  padding: 0.7rem;
}

.header a {
  color: #ffffff;
  padding-right: 0.3rem;
  text-decoration: none;
}
</style>
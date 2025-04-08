

<template>
  
    
      <nav>
        <!-- <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink> -->
        <RouterLink :to="{name: 'home'}">Home</RouterLink>
        <RouterLink :to="{name: 'about'}">About</RouterLink>
        <RouterLink :to="{name: 'jobs'}">Jobs</RouterLink>

      </nav>
    <RouterView />
</template>
<script >
import { RouterLink, RouterView } from 'vue-router'

</script>

<style>
nav {
  padding: 30px
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  padding: 10px;
  border-radius: 4px;
}

nav a.router-link-exact-active {
  color: white;
  background: red;
}

</style>

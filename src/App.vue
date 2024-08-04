<template>
  <nav>
    <router-link to="/">Home</router-link> 🤷🏽‍♂️
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
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
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

button {
  width: 80%;
  padding: 1.5rem;
  border-radius: 8px;
  border-style: none;
  background-color: #dffff0;
  font-weight: 900;
  color: #42b983;
}
</style>

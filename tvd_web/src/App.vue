<template>
  <div id = "logo">
    <img src = "../src/assets/tvd_logo.png">
  </div>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/services">Services</router-link>
    <router-link to="/contact">Contact</router-link>
    <!--Need to add more router links to the different pages -->
  </nav>
<div id = "router">
  <router-view/>
</div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#router{
  /* Need something here to spice it up*/
}

body{
  background: black;
}

#logo img{
  max-height: auto;
  width: 25%;
}

nav {
  padding: 30px;
}

nav a {
  font-size: 150%;
  font-weight: bold;
  padding: 3em;
  color:rgba(255, 228, 196, 0.822);
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

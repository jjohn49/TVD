<template>
<div class = "bg-black">
  <div class = "flex items-center justify-center">
    <img class = "w-1/4" src = "../src/assets/tvd_logo.png">
  </div>
  <nav class = "flex items-center justify-center space-x-10">
    <router-link class = "text-slate-600 hover:text-stone-400" to="/">Home</router-link>
    <router-link class = "text-slate-600 hover:text-stone-400" to="/about">About</router-link>
    <router-link  class = "text-slate-600 hover:text-stone-400" to="/services">Services</router-link>
    <router-link class = "text-slate-600 hover:text-stone-400" to="/contact">Contact</router-link>
    <!--Need to add more router links to the different pages -->
  </nav>
<div class="bg-gray-700">
  <router-view/>
</div>
</div>
</template>

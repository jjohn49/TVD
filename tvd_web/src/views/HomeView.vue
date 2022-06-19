<template>
  <div class="home">
    <TVDHome/>
  </div>
  <div class = "paragraph">
    <p>
      Since 1953, Talcott View Development has delivered on providing quality services for Connecticut
    </p>
  </div>
  <div class = "Rosewood">
    <img src = "../assets/12_Rosewood_1964.jpg">
  </div>
</template>

<script>
// @ is an alias to /src
import TVDHome from '../components/TVDHome.vue'

export default {
  name: 'HomeView',
  components: {
    TVDHome
  }
}
</script>

<style scoped>
.paragraph p{
  padding: 1em;
  color:rgba(255, 228, 196, 0.822);
  float: left;
}

.Rosewood img{
  width: 35%;
  padding: 1em;
}
</style>

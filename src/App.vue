<template>
  <header class="header" id="navbar">
    <router-link to="/" class="active"><img src="@/assets/logo.png" alt="Logo" class="logo"></router-link>
    <nav class="nav">
      <router-link to="/" class="active">home</router-link>
      <router-link to="/about" class="active">about</router-link>
      <router-link to="/projects" class="active">projects</router-link>
      <router-link to="/creatives" class="active">creatives</router-link>
      <router-link to="/resume" class="active">resume</router-link>
    </nav>
  </header>
  <router-view/>
</template>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#navbar {
  position: fixed; /* Make it stick/fixed */
  top: 0; /* Stay on top */
  width: 100%; /* Full width */
  transition: top 0.3s; /* Transition effect when sliding down (and up) */
}

.header{
  grid-area: header;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 1em;
  position: fixed;
  width: 100%;
}

.header .logo{
  width: 5em;
  padding: 0em 1em;
}

.header .nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  color: rgb(225, 135, 40);
  padding-right: 10px;
  margin: 0 1em;
  font-weight: bold;
  margin-right: 2em;
}

.header .nav a:hover, .header .nav a .active{
  color: rgb(224, 160, 91);
}

.header .nav a.router-link-exact-active {
  /* color: rgb(224, 185, 143); */
  color: rgb(225, 135, 40);
}

</style>


<script>
/* When the user scrolls down, hide the navbar. When the user scrolls up, show the navbar */
var prevScrollpos = window.pageYOffset;
window.onscroll = function() {
  var currentScrollPos = window.pageYOffset;
  if (prevScrollpos > currentScrollPos) {
    document.getElementById("navbar").style.top = "0";
  } else {
    document.getElementById("navbar").style.top = "-100px";
  }
  prevScrollpos = currentScrollPos;
}
</script>
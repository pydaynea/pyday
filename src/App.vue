<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.navbar.is-dark {
  background: transparent;
}
.navbar-item {
  color: #ffffff;
  font-weight: bold;
  font-size: 16px;
}
.navbar-burger {
  width: 5rem;
  height: 5rem;
}
.navbar-menu.is-active .navbar-item {
  color: #ffffff;
}
@media screen and (max-width: 1023px) {
  .navbar-menu.is-active {
    background: rgba(0, 0, 0, 0.50);
  }
  a.navbar-item:hover, a.navbar-item.is-active, a.navbar-link:hover, a.navbar-link.is-active {
    background: none;
  }
}
.navbar-item img {
  max-height: 3.75rem;
  height: 3.75rem;
}
.lower-wave {
  z-index: 1;
  width: 100%;
  width: 100%;
  display: block;
}
</style>

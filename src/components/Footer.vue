<template>
<div class="section">
  <img class="snake" src="@/assets/snake.svg">
  <div class="container">
    <nav class="navbar is-dark">
      <div class="navbar-menu is-active">
        <div class="navbar-end">
          <a class="navbar-item">¿Qué es una PyDay?</a>
          <a class="navbar-item">Agenda</a>
          <a class="navbar-item">Lugar</a>
          <a class="navbar-item">Sponsors</a>
          <a class="navbar-item">Contacto</a>
          <a class="navbar-item">Registrarse</a>
        </div>
      </div>
    </nav>
  </div>
</div>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.snake {
  width: 30%;
  position: absolute;
  top: -38%;
  left: -5px;
  min-width: 300px;
  z-index: 1;
}
.section {
  background: #1D2533;
  padding-top: 50px;
  position: relative;
  min-height: 300px;
}
.navbar-menu {
    background: none;
    box-shadow: none;
}
</style>

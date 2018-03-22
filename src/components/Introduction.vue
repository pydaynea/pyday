<template>
  <div>
    <div class="section">
      <div class="container">
        <div class="columns is-centered">
          <div class="column is-5">
            <div class="title">
              <div></div>
              <span>
                ¿Qué es una PyDay?
              </span>
            </div>
          </div>
        </div>

        <div class="columns"></div>

        <div class="columns is-centered">
          <div class="column is-6 has-text-centered text">
            <p>
              El Python Day es un evento libre y gratuito que dura un día, en donde tendrán lugar pequeños cursos y charlas relacionadas a este lenguaje que de a poco va haciendo su lugar entre los desarrolladores.
            </p>
            <p>
              Tenemos como intención hacer un espacio en donde cualquier persona interesada pueda acercarse a <b>preguntar</b>, <b>aprender</b> y <b>experimentar</b> con estas herramientas
            </p>
          </div>
        </div>
      </div>
    </div>
    <img class="lower-wave" src="/static/intro-lower-wave.svg">
  </div>
</template>

<script>
export default {
  name: 'Introduction',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container {
    padding: 50px 0 80px 0;
  }
  .title {
    color: #1D2533;
    position: relative;
    text-align: center;
  }
  .title div {
    background: #F2D24C;
    width: 100%;
    display: block;
    position: absolute;
    left: 0;
    top: -1px;
    height: 18px;
    margin-top: 12px;
    border-radius: 17px;
  }
  .title span {
    position: relative;
  }
  p {
    font-weight: 300;
    font-style: italic;
    padding: 10px 0;
  }
</style>

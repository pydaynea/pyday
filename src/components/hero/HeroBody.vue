<template>
  <div class="hero-body">
    <div class="container title-wrap has-text-centered">
      <div class="title1">
        DE LA COMUNIDAD
      </div>
      <div class="title2">
        PARA LA COMUNIDAD
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroBody',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .title-wrap {
    max-width: 500px
  }
  .title1 {
    text-align: left;
    font-weight: bold;
    font-size: 28px;
    font-style: italic;
    color: #FFFFFF;

  }
  .title2 {
    text-align: right;
    font-weight: bold;
    font-size: 39px;
    font-style: italic;
    color: #F2D24C;
  }
</style>

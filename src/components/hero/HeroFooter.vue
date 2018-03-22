<template>
  <div class="hero-foot">
    <div class="container">
      <div class="columns is-centered">
          <div class="column is-4 has-text-centered">
            <div class="level">
              <span class="date level-item">
                <img src="/static/calendar.svg" alt="pyday calendar">
                12 de Mayo
              </span>
              <span class="place level-item">
                <img src="/static/pin.svg" alt="pyday calendar">
                La Plata · 50 y 120
              </span>
            </div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroFooter',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .date, .place {
    color: #ffffff;
    font-weight: bold;
    padding: 0 10px;
    font-size: 20px
  }
  .hero-foot {
    padding-bottom: 50px
  }
  .hero-foot img {
    height: 2rem;
  }
</style>

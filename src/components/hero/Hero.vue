<template>
<section class="hero is-medium">
  <img class="hero-bg" src="@/assets/hero.jpg"/>
  <!-- Hero head: will stick at the top -->
  <hero-head/>
  <!-- Hero content: will be in the middle -->
  <hero-body/>
  <!-- Hero footer: will stick at the bottom -->
  <hero-footer/>
  <img class="lower-wave" src="@/assets/hero-lower-wave.svg">
</section>
</template>

<script>
import HeroHead from './HeroHead.vue'
import HeroBody from './HeroBody.vue'
import HeroFooter from './HeroFooter.vue'

export default {
  name: 'Hero',
  data () {
    return {
    }
  },
  components: {
    'hero-head': HeroHead,
    'hero-body': HeroBody,
    'hero-footer': HeroFooter
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hero {
  position: relative;
  background: #2e3440;
}
.hero-bg {
  position: absolute;
  left: 0;
  right: 0;
  object-fit: cover;
  height: 100%;
  width: 100%;
}
</style>

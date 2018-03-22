<template>
  <div class="content">
    <hero/>
    <introduction/>
    <agenda/>
    <sponsors/>
    <footer-section/>
  </div>
</template>

<script>
import Hero from './hero/Hero.vue'
import Introduction from './Introduction.vue'
import Agenda from './Agenda.vue'
import Sponsors from './Sponsors.vue'
import Footer from './Footer.vue'

export default {
  name: 'Landing',
  data () {
    return {
    }
  },
  components: {
    'hero': Hero,
    'introduction': Introduction,
    'agenda': Agenda,
    'sponsors': Sponsors,
    'footer-section': Footer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

<template>
<div class="agenda yellow">

  <div class="section" id="agenda">
    <div class="container is-paddingless">
      <div class="wrap">
        <div class="title">
          <div></div>
          <span>
            Agenda
          </span>
        </div>
      </div>
    </div>
  </div>

  <div class="section agenda-talks">
    <credentials :time="'09:30 HS'"></credentials>
    <tracks :tracks="tracks"></tracks>
    <template v-for="item in agenda">
      <talk-item v-if="item.placement !== 'break'" :talk="item" :key="item.time"></talk-item>
      <break v-if="item.placement === 'break'" :key="item.time" :time="item.time"></break>
    </template>
    <p class="coc-wrap">
      Durante el evento les pedimos a todos que respeten nuestro <router-link class="coc-link" :to="{name:'coc'}">código de conducta</router-link>
    </p>
  </div>

  <img class="lower-wave" src="@/assets/agenda-lower-wave.svg">
</div>
</template>

<script>
import TalkItem from './TalkItem.vue'
import Break from './Break.vue'
import Tracks from './Tracks.vue'
import Credentials from './Credentials.vue'
export default {
  name: 'Agenda',
  computed: {
    agenda: function () {
      for (let index = 0; index < this.tracks.length; index++) {
        const element = this.tracks[index]
        if (element.active) {
          return element.agenda
        }
      }
    }
  },
  data () {
    return {
      tracks: [
        {
          name: 'Salón principal',
          active: true,
          agenda: [
            {
              author: 'Facundo Batista',
              description: '¿Cómo debuguear código Python?',
              time: '10:00HS',
              placement: 'left'
            },
            {
              author: 'Maria Andrea Vignau',
              description: 'Celular, un testigo posible y silencioso',
              time: '11:00HS',
              placement: 'right'
            },
            {
              author: 'Juan Pedro Fisanotti',
              description: 'Prediciendo los partidos del Mundial con Inteligencia Artificial',
              time: '12:00HS',
              placement: 'left'
            },
            {
              placement: 'break',
              time: '13:00'
            },
            {
              author: 'Felipe Sodre Barros',
              description: 'Aprendiendo Python con Raspberry Pi',
              time: '14:00HS',
              placement: 'left'
            },
            {
              author: 'Gary Servin',
              description: 'Taller de RoDI (Robot Didáctico Inalámbrico) con Python',
              time: '15:00HS',
              placement: 'right'
            },
            {
              author: 'Cristhian Boujon',
              description: 'Análisis de datos con Pandas',
              time: '16:00HS',
              placement: 'left'
            },
            {
              author: 'Finalización del evento',
              description: 'Cierre y Conclusiones de la Jornada',
              time: '17:00HS',
              placement: 'right'
            }
          ]
        }
      ]
    }
  },
  components: {
    'talk-item': TalkItem,
    'break': Break,
    'credentials': Credentials,
    'tracks': Tracks
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

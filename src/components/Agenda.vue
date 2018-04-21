<template>
<div id="agenda" class="agenda yellow">
  <div class="section">
    <div class="container">
      <div class="wrap">
        <div class="title">
          <div></div>
          <span>
            Oradores
          </span>
        </div>
        <div></div>
      </div>
      <!-- replicar esta columns para agregar una nueva fila -->
      <div class="columns">
        <!-- solo replicar esta columna para otros oradores. Se recomiendan 2 por fila-->
        <div class="column">
          <div class="box speaker">
            <article class="media">
              <figure class="image is-600x600">
                <img src="@/assets/oradores/facundo_batista.png" alt="Facundo Batista">
              </figure>
            </article>
            <div class="content">
              <strong>Facundo Batista</strong>
              <span class="is-pulled-right">
                <a href="https://twitter.com/facundobatista/">
                  <icon name="brands/twitter" scale="1"></icon>
                </a>
                <a href="http://www.taniquetil.com.ar">
                  <icon name="brands/chrome" scale="1"></icon>
                </a>
                <a href="https://github.com/facundobatista">
                  <icon name="brands/github" scale="1"></icon>
                </a>
                <a href=" https://ar.linkedin.com/in/facundobatista">
                  <icon name="brands/linkedin" scale="1"></icon>
                </a>
              </span>
              <read-more more-str="Leer más" :text="facu_bio" link="#" less-str="Leer menos" :max-chars="375"></read-more>
            </div>
          </div>
        </div>
        <div class="column">
          <div class="box speaker">
            <article class="media">
              <figure class="image is-600x600">
                <img src="@/assets/oradores/marian_vignau.png" alt="Marian Vignau">
              </figure>
            </article>
            <div class="content">
              <strong>Marian Vignau</strong>
              <span class="is-pulled-right">
                <a href="https://twitter.com/mavignau/">
                  <icon name="brands/twitter" scale="1"></icon>
                </a>
                <a href="https://github.com/marian-vignau">
                  <icon name="brands/github" scale="1"></icon>
                </a>
                <a href="https://www.linkedin.com/in/maría-andrea-vignau-77ba1623">
                  <icon name="brands/linkedin" scale="1"></icon>
                </a>
              </span>
              <read-more more-str="Leer más" :text="marian_bio" link="#" less-str="Leer menos" :max-chars="375"></read-more>
            </div>
          </div>
        </div>
      </div>

      <div class="columns">
        <!-- solo replicar esta columna para otros oradores. Se recomiendan 2 por fila-->
        <div class="column">
          <div class="box speaker">
            <article class="media">
              <figure class="image is-600x600">
                <img src="@/assets/oradores/fisa.png" alt="Juan Pedro Fisanotti">
              </figure>
            </article>
            <div class="content">
              <strong>Juan Pedro Fisanotti</strong>
              <span class="is-pulled-right">
                <a href="https://twitter.com/fisadev">
                  <icon name="brands/twitter" scale="1"></icon>
                </a>
                <a href="https://github.com/fisadev">
                  <icon name="brands/github" scale="1"></icon>
                </a>
              </span>
              <read-more more-str="Leer más" :text="fisa_bio" link="#" less-str="Leer menos" :max-chars="375"></read-more>
            </div>
          </div>
        </div>
        <div class="column">
        </div>
      </div>
      <div class="notification is-info">
        Podés mandar tu charla hasta el
        <strong>2 de mayo</strong>.
      </div>

      <p>
        Te invitamos a postularte como orador para nuestro próximo evento.
        Para el evento buscamos que la comunidad comparta su conocimiento. Para eso, vamos a hacer una búsqueda pública de oradores.
        Vamos a elegir a 6 de los postulantes. Para participar de este proceso sólo tenés que completar este formulario.
      </p>

      <p>
        <a target="_blank" href="https://goo.gl/forms/iL1hx0iJynLTbW7u2" class="button is-link">Participá como orador</a>
      </p>

    </div>
  </div>
  <img class="lower-wave" src="@/assets/agenda-lower-wave.svg">
</div>
</template>

<script>

export default {
  name: 'Agenda',
  data () {
    return {
      fisa_bio: `Desarrollo usando principalmente Python desde hace ya bastante tiempo,
                y soy miembro activo de PyAr. He hecho mucho desarrollo web, algo de escritorio,
                y bastante de Inteligencia Artificial (Machine Learning y otras cosas).
                Hoy en día hago software para satélites en Satellogic, además de dar clases
                en la UCSE DAR y practicar artes marciales medievales.`,
      facu_bio: `Facundo Batista es Ingeniero en Electrónica egresado de la Universidad Nacional de La Matanza y
                cuenta  con un Máster en Ingeniería de la Innovación de la Universidad de Bologna, Italia.<br>
                Desde hace más de 10 años se encuentra trabajando con Python en
                <a href="https://www.canonical.com">Canonical</a>,
                dentro del equipo de Online Services. <br>
                Facundo realmente ama Python, ya que habiéndose convertido en desarrollador oficial del lenguaje
                formó parte de la Python Software Foundation hasta que  finalmente fundó
                <a href="http://www.python.org.ar">Python Argentina</a>
                Fue invitado como expositor a numerosas conferencias nacionales e internacionales y siguiendo
                con su espirítu docente dictó cursos de Python en universidades, terciarios, empresas y particulares
                (<a href="http://www.taniquetil.com.ar/facundo/cursoPython.html">Ver curso</a>).<br>
                Además colabora activamente en proyectos de software libre, entre los que podemos encontrar a CDPedia,
                Encuentro, Fades, Lalita, Magicicada, Launcherposta, Enjuewemela, Linkode entre otros.`,
      marian_bio: `Soy María Andrea Vignau, Ingeniera en Sistemas de Información,
                  trabajo como Perito Informático Oficial en el Gabinete Cientifico del Ministerio
                  Público Fiscal Poder Judicial de la Provincia del Chaco.
                  Últimamente estoy colaborando con las comunidades de software libre, como 
                  socia de Asociación Civil Python Argentina, y coorganizadora del Festival 
                  de Instalación de Software Libre, que hacemos en el Centro Cultural Alternativo 
                  de Resistencia el 28 de Abril, y del Python Day NEA en el Club de Emprendedores
                  en Corrientes el 19 de mayo. Así como de 2600 filial Resistencia.`
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

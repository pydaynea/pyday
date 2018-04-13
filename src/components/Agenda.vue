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
      <div class="">
        <div class="columns">
          <div class="column">
            <div class="box">
              <article class="media">
                <div class="media-left">
                  <figure class="image is-400x400">
                    <img src="@/assets/facundo_batista.jpg" alt="Facundo Batista">
                  </figure>
                </div>
                <div class="media-content">
                  <div class="content">
                    <strong>Facundo Batista</strong>
                    <div>
                      <a href="https://twitter.com/facundobatista/">
                        <icon name="brands/twitter" scale="1"></icon>
                      </a>
                      <a href="https://github.com/facundobatista">
                        <icon name="brands/chrome" scale="1"></icon>
                      </a>
                      <a href="https://github.com/facundobatista">
                        <icon name="brands/github" scale="1"></icon>
                      </a>
                      <a href=" https://ar.linkedin.com/in/facundobatista">
                        <icon name="brands/linkedin" scale="1"></icon>
                      </a>
                    </div>
                    <p>
                      Facundo Batista es Ingeniero en Electrónica egresado de la Universidad Nacional de La Matanza y
                      cuenta  con un Máster en Ingeniería de la Innovación de la Universidad de Bologna, Italia.<br>
                      Desde hace más de 10 años se encuentra trabajando con Python en
                      <a href="https://www.canonical.com">Canonical</a>,
                      dentro del equipo de Online Services.
                    </p>
                    <p>
                      Facundo realmente ama Python, ya que habiéndose convertido en desarrollador oficial del lenguaje
                      formó parte de la Python Software Foundation hasta que  finalmente fundó
                      <a href="http://www.python.org.ar">Python Argentina</a>. <br>
                      Fue invitado como expositor a numerosas conferencias nacionales e internacionales y siguiendo
                      con su espirítu docente dictó cursos de Python en universidades, terciarios, empresas y particulares
                      (<a href="http://www.taniquetil.com.ar/facundo/cursoPython.html">Ver curso</a>).<br>
                      Además colabora activamente en proyectos de software libre, entre los que podemos encontrar a CDPedia,
                      Encuentro, Fades, Lalita, Magicicada, Launcherposta, Enjuewemela, Linkode entre otros.
                    </p>
                  </div>
                </div>
              </article>
            </div>
          </div>
        </div>
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
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

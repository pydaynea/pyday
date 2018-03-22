<template>
<div class="yellow">
  <div class="section">
    <div class="container">
      <div class="wrap">
        <div class="title">
          <div></div>
          <span>
            Agenda
          </span>
        </div>
      </div>
      <p>
        Estamos buscado orandores
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
.container {
  padding-bottom: 100px;
}
.yellow {
  background: #F2D24C;
  padding-top: 50px;
}
.wrap {
  width: 200px;
}
.title {
  color: #1D2533;
  position: relative;
  text-align: center;
}
.title div {
  background: #ffffff;
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

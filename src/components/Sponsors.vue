<template>
<div class="section">
  <div class="container">
    <div class="wrap">
      <div class="title">
        <div></div>
        <span>
          Nos apoyan
        </span>
      </div>
    </div>
    <p>
      Estamos buscado sponsors
    </p>
  </div>
</div>
</template>

<script>
export default {
  name: 'Sponsors',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  padding-bottom: 200px;
}

.wrap {
  width: 300px;
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

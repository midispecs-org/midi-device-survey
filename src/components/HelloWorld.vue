<template>
  <div class="hello">
    <h1>{{ message }}</h1>
    <h2>A Survey of MIDI Hardware by the <a href="https://midispecs.org/about">midispecs.org</a> project.</h2>

  </div>
</template>
<script src="https://cdn.jsdelivr.net/npm/jzz"></script>
<script src="https://cdn.jsdelivr.net/npm/jzz-midi-gear"></script>
<script>
export default {
  name: 'HelloWorld',
  props: {
    message: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

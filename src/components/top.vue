<template>
  <div class="top">
   <top>{{top}}</top>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      top:"我还可以和你一起并肩作战么？"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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

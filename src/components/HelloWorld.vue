<template>
  <div class="hello">
    <h1>Project Finch</h1>
    <h2>{{ msg }}</h2>
    <p>
      Check out the 
      <a href="https://tobias.dappjump.io" target="_blank" rel="noopener">creator's portfolio</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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

<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Entre em contato com <a href="mailto:caiogfreire@gmail.com">caiogfreire@gmail.com</a>
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
  color: #FF0000;
}
</style>

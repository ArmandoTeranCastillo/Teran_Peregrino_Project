<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Lleva un análisis y seguimiento de tu proceso de producción de forma remota y <br>
      Además de poder crear tus nóminas de manera automática, y dar un vistazo a las finanzas de tu negocio
    </p>
    <h3>Desarrollado con:</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">Vue JS</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">.NET Core 6</a></li>
    </ul>
    <h3>Alojado en:</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Azure</a></li>
    </ul>
    <h3>Para la empresa:</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">TERAN PEREGRINO HERMANOS SA de CV</a></li>
    </ul>
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
  color: #42b983;
}
</style>

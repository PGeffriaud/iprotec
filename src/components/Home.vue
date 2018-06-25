<template>
  <div class="homepage">
    <h1>Welcome to your improved eprotec experience !</h1>
    <h2>Navigate through the app</h2>
    <ul>
      <li>
        <a href="https://vuejs.org">Events
        </a>
      </li>
      <li>
        <a href="https://forum.vuejs.org"> People</a>
      </li>
    </ul>
    <h2>Additional links</h2>
    <ul>
      <li>
        <a href="https://www.facebook.com/ProtectionCivile.LoireAtlantique/" target="_blank">Facebook</a>
      </li>
      <li>
        <a href="https://twitter.com/ProtecCivile" target="_blank">Twitter</a>
      </li>
    </ul>
    <h2>Development helps</h2>
    <ul>
      <li>
        <a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a>
      </li>
      <li>
        <a href="https://vuetifyjs.com/en/getting-started/quick-start" target="_blank">Vuetify</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome to your improved eprotec experience !'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
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
  color: #F98400;
}
</style>

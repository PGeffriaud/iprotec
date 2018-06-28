<template>
  <v-container text-xs-center class="homepage">
    <v-layout row>
      <v-flex xs6 offset-xs3>
        <img src="../assets/logo.png">
      </v-flex>
    </v-layout>
    <v-layout row>
      <v-flex xs12>
        <h1>Welcome to your improved eprotec experience !</h1>
      </v-flex>
    </v-layout>
    <v-layout row>
      <v-flex xs4>
        <h2>Navigate through the app</h2>
      </v-flex>
      <v-flex xs4>
        <h2>Additional links</h2>
      </v-flex>
      <v-flex xs4>
        <h2>Development helps</h2>
      </v-flex>
    </v-layout>
    <v-layout row>
      <v-flex xs4>
        <v-btn color="primary" href="people"><v-icon left>people</v-icon>Events</v-btn>
        <v-btn color="primary" href="events"><v-icon left>event</v-icon>People</v-btn>
      </v-flex>
      <v-flex xs4>
        <a href="https://www.facebook.com/ProtectionCivile.LoireAtlantique/" target="_blank">Facebook</a>
        <a href="https://twitter.com/ProtecCivile" target="_blank">Twitter</a>
      </v-flex>
      <v-flex xs4>
        <a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a>
        <a href="https://vuetifyjs.com/en/getting-started/quick-start" target="_blank">Vuetify</a>
        <a href="https://material.io/tools/icons/?style=baseline" target="_blank">Icons</a>
      </v-flex>
    </v-layout>
  </v-container>
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

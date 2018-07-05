<template lang='pug'>
  div(class='homepage')
    v-layout(row)
      v-flex(xs6 offset-xs3)
        img(src='../assets/logo.png')
        h1 Welcome to my new Vue project
        v-btn(color='primary' href='#/events') Events
          v-icon(right) event
        v-btn(color='secondary' href='#/people') People
          v-icon(right) people
    v-layout(row class='additional-links')
      v-flex(xs6 offset-xs3)
        h2 More links
        ul
          li(v-for='item in links')
            a(:href='item.url' target='_blank') {{item.text}}
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      links: [
        {url: 'http://vuejs-templates.github.io/webpack/', text: 'Docs for this template'},
        {url: 'https://vuetifyjs.com/en/getting-started/quick-start', text: 'Vuetify.js'},
        {url: 'https://material.io/tools/icons/?style=baseline', text: 'Icons'},
        {url: 'https://pugjs.org/api/getting-started.html', text: 'Pug.js'}
      ]
    }
  }
}
</script>

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
.additional-links {
  margin-top: 50px;
}
</style>

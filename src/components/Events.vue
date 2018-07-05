<template lang='pug'>
  div
    h1 Incoming events
    ul
      li(v-for='x in values') Event {{x}}
</template>

<script>
export default {
  name: 'Events',
  data () {
    return {
      values: [1, 2, 3, 4],
      msg: 'Event'
    }
  }
}
</script>

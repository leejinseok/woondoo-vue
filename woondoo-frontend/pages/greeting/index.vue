<template>
  <div class="greetingPage">
    <Header /> 
  </div>
</template>

<script>
import { mapState } from 'vuex'
import Header from '~/components/shared/Header'

export default {
  fetch({ store }) {
  },
  computed: mapState([
    'counter'
  ]),
  methods: {
  },
  components: {
    Header
  }
}
</script>

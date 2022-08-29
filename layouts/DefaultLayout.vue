<template>
  <b-container fluid="sm">
    <Header />
    <Nuxt />
    <Footer />
  </b-container>
</template>

<script lang="ts">
import Header from '~/components/default/Header.vue'
import Footer from '~/components/default/Footer.vue'

export default {
  name: 'DefaultLayout',
  components: { Footer, Header },
}
</script>

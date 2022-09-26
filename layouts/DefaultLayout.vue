<template>
  <b-container fluid="sm">
    <DefaultHeader />
    <Nuxt />
    <DefaultFooter />
  </b-container>
</template>

<script lang="ts">
import DefaultHeader from '~/components/default/DefaultHeader.vue'
import DefaultFooter from '~/components/default/DefaultFooter.vue'

export default {
  name: 'DefaultLayout',
  components: { DefaultFooter, DefaultHeader },
}
</script>

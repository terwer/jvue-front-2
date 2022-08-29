<template>
  <HomePosts />
</template>

<script lang="ts">
import Vue from 'vue'
import HomePosts from '~/components/default/HomePosts.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: { HomePosts },
  layout: 'DefaultLayout',
})
</script>

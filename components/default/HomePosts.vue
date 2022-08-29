<template>
  <div>
    <b-list-group>
      <b-list-group-item>Cras justo odio</b-list-group-item>
      <b-list-group-item>Dapibus ac facilisis in</b-list-group-item>
      <b-list-group-item active>Morbi leo risus</b-list-group-item>
      <b-list-group-item>Porta ac consectetur ac</b-list-group-item>
      <b-list-group-item>Vestibulum at eros</b-list-group-item>
    </b-list-group>

    <div class="overflow-auto jvue-pager">
      <b-pagination-nav :link-gen="linkGen" :number-of-pages="10" use-router></b-pagination-nav>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: 'HomePosts',
  methods: {
    linkGen(pageNum: number) {
      return pageNum === 1 ? '?' : `?page=${pageNum}`
    }
  }
}
</script>

<style scoped>
.jvue-pager{
  margin-top: 10px;
}
</style>

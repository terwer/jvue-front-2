<template>
  <div class="jvue-navbar">
    <b-navbar toggleable="lg" type="dark" variant="light">
      <b-navbar-brand href="#">LOGO</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">文章</b-nav-item>
          <b-nav-item href="#" disabled>随笔</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Search"
            ></b-form-input>
            <b-button size="sm" variant="primary" type="submit"
              >Search</b-button
            >
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Header',
}
</script>

<style scoped>
.jvue-navbar {
  margin: 10px 0;
}

.jvue-navbar .navbar-dark .navbar-brand {
  color: #212529;
}

.jvue-navbar .navbar-dark .navbar-nav .nav-link {
  color: #212529;
}
</style>

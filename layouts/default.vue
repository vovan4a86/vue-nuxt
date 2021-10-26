<template>
  <div>
    <!-- navigation -->
    <nav class="navbar has-shadow" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-start">
          <nuxt-link to="/" class="navbar-item">
            Vue-Nuxt Site
          </nuxt-link>
          <nuxt-link active-class="is-active" to="/" class="navbar-item is-tab" exact>Home</nuxt-link>
          <nuxt-link active-class="is-active" to="/about" class="navbar-item is-tab" exact>About</nuxt-link>
          <nuxt-link active-class="is-active" to="/features" class="navbar-item is-tab" exact>Features</nuxt-link>
        </div>
      </div>
    </nav>
    <!-- /navigation -->

    <!-- displays the page component -->
    <nuxt/>
  </div>
</template>

<script>
export default {
  name: "default"
}
</script>

<style scoped>
.main-content {
  margin: 30px 0;
}
</style>

<template>
  <div>
    <section class="hero is-medium is-primary is-bold">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Welcome to the JavaScript SSR Blog.
          </h1>
          <h2 class="subtitle">
            Hope you find something you like.
          </h2>
        </div>
      </div>
    </section>
    <section class="p-12">
      <div class="container text-center bg-blue-600 p-8">
        <h2 class="text-7xl font-bold">Tailwind CSS rulezzzz!</h2>
        <p>Lorem ipsum dolores sit amet.</p>
      </div>
    </section>
    <posts />
  </div>
</template>

<script>
import Posts from '~/components/Posts.vue'
export default {
  components: {
    Posts
  },
  head: {
    title: 'Home'
  },
}
</script>

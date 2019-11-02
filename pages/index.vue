<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        aketato
      </h1>
      <h2 class="subtitle">
        My cat&#39;s meow Nuxt.js project
      </h2>
      <v-btn small>Normal</v-btn>
      <v-btn small>Normal</v-btn>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style lang="scss">
  .title {
    font-size: 100px;
  }
</style>

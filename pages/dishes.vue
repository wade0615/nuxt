<template>
  <div class="container">
    <h2>
      {{ title }}
    </h2>
    <nuxt-link to="/">
      點我回 home
    </nuxt-link>
  </div>
</template>

<script>
export default {
  data () {
    return {
      title: 'I am dishes page.'
    }
  }
}
</script>

<style lang="sass" scoped>
.container
  font-size: 20px
  margin: 0 auto
  min-height: 100vh
  display: flex
  justify-content: center
  align-items: center
  text-align: center
</style>

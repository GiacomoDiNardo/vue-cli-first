<template>
  <div>
    <PageTitle></PageTitle>
    <Hero></Hero>
  </div>
</template>

<script>
import PageTitle from "./components/PageTitle.vue";
import Hero from "./components/HeroJumbo.vue"

export default {
  components: {
    PageTitle,
    Hero,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

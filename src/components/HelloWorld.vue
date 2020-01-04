<template>
  <section>
    <Header></Header>
    <Hero></Hero>
    <Advantages></Advantages>
  </section>
</template>
<script>
import Header from './Header'
import Hero from './Hero'
import Advantages from './Advantages'
export default {
  components: {
    Hero,
    Header,
    Advantages
  }
}
</script>
<style scoped lang="scss">
  .hero-body {
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("../assets/jeshoots-com-5EKw8Z7CgE4-unsplash.jpg") no-repeat center center fixed;
  }
  .hero-title {
    color: #3fb2f0;
  }
</style>

<template>
  <section class="hero is-fullheight is-info">
    <div class="hero-head">
    </div>
    <div class="hero-body">
      <div class="container has-text-right">
        <div class="column is-7 is-offset-5">
          <h1 class="hero-title title">
            Lorem ipsum is <br>
            Simple dummy Text
          </h1>
          <p class="subtitle">
            Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped lang="scss">
  .hero-body {
    background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url("../assets/jeshoots-com-5EKw8Z7CgE4-unsplash.jpg") no-repeat center center fixed;
  }
  .hero-title {
    color: #3fb2f0;
    text-transform: uppercase;
    font-size: 34px;
  }
</style>

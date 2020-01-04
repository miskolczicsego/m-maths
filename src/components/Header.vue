<template>
    <header>
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item" href>
              <img src="../assets/site_logo.png" width="220px">
            </a>
            <div class="navbar-burger has-text-black" @click="showNav = !showNav" :class="{ 'is-active': showNav }">
              <span></span>
              <span></span>
              <span></span>
            </div>
          </div>
          <div class="navbar-menu" :class="{ 'is-active': showNav }">
            <div class="navbar-end">
                    <span class="navbar-item">
                     <a>Teachers</a>
                   </span>
              <span class="navbar-item">
                     <a>About us</a>
                   </span>
              <div class="navbar-item">
                <a>Log in</a>
              </div>
              <div class="navbar-item">
                <a>Sign up</a>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </header>
</template>

<script>
export default {
  name: 'Header.vue',
  data () {
    return {
      showNav: false
    }
  }

}
</script>

<style scoped lang="scss">
 header {
   padding-top: 8px;
   min-height: 65px;
 }
  .navbar-item {
    color: black;
  }
</style>

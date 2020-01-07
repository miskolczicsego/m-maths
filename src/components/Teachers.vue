<template>
    <div class="section content-container teachers">
      <div class="columns is-centered">
        <div class="column is-4 has-text-centered">
          <div class="title">Our teachers</div>
          <hr width="25%" class="teachers-hr">
          <div class="subtitle">
            Lorem ipsum dolor set
          </div>
        </div>
      </div>

      <div class="columns is-centered">
        <div class="column is-one-third">
          <figure class="image is-140x140">
            <img :src="image" alt="" class="is-rounded">
          </figure>
        </div>
        <div class="column is-two-thirds has-text-centered is-vcentered">
          <p class="has-text-right is-size-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. In dapibus feugiat consequat. Ut tortor odio, pharetra sed feugiat ullamcorper, facilisis eget nulla. Aenean consequat sapien et justo feugiat, ac pellentesque purus aliquet. </p>
        </div>
      </div>
    </div>
</template>
<!--<script src="node_modules/faker/index.js"></script>-->
<script>
import faker from 'faker'
export default {
  name: 'Teachers',

  data () {
    return {
      image: faker.image.avatar()
    }
  }
}
</script>

<style scoped>

  .teachers-hr {
      border: 2px solid blue;
      margin: 0 auto;
  }
  .is-vcentered {
    display: flex;
    align-items: center;
    align-content: center;
  }
  .content-container {
    padding-top: 35px;
  }
  .teachers {
    background-color: lightblue;
  }
</style>

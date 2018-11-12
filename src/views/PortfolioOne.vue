<template>
  <div class="home main-content">
    <div class="left-content slideUp">
      <h1>
        CRYPTO LOGO
      </h1>
      <p class="subxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subxtext">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt quod eius cupiditate facere, tempora eaque. Neque, ut natus non tempore obcaecati iure asperiores explicabo similique praesentium, veniam eveniet corporis hic.</p>
      <router-link to="portfolio/two">
        <img src="../assets/arrow-down.svg" alt="arrow down" class="arrow arrow-down">
      </router-link>
    </div>
    <div class="right-content img2">
      <img src="../assets/logo.svg" alt="logo">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'one',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  $page_color: #625B7E;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: $page_color;

    img {
      width: 50%;
    }
  }
</style>


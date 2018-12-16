<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>
        5 YRS DESIGN
      </h1>
      <p class="subxtext">Simone has been a full stack developer for 3 years and a frontend developer for the last 2 years.</p>
      <p class="subxtext">I've studied with Udacity, Udemy, Lynda, EdX and more.</p>
    </div>
    <div class="right-content img1">
      <button>
        <router-link to="portfolio/one">Browse Work</router-link>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style scoped>
  .img1 {
    background: url('../assets/home.jpg')
  }
</style>

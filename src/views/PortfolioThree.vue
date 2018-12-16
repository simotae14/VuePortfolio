<template>
  <div class="three main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/two">
        <img src="../assets/arrow-up.svg" alt="arrow up" class="arrow arrow-up">
      </router-link>
      <h1>
        PRINT
      </h1>
      <p class="subxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subxtext">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt quod eius cupiditate facere, tempora eaque. Neque, ut natus non tempore obcaecati iure asperiores explicabo similique praesentium, veniam eveniet corporis hic.</p>
    </div>
    <div class="right-content img2">
    </div>
  </div>
</template>

<script>
export default {
  name: 'three'
}
</script>

<style lang="scss" scoped>
  $page_color: #5487A8;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/card.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }
</style>

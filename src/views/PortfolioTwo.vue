<template>
  <div class="two main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/one">
        <img src="../assets/arrow-up.svg" alt="arrow up" class="arrow arrow-up">
      </router-link>
      <h1>
        MOBILE UI
      </h1>
      <p class="subxtext">Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subxtext">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt quod eius cupiditate facere, tempora eaque. Neque, ut natus non tempore obcaecati iure asperiores explicabo similique praesentium, veniam eveniet corporis hic.</p>
      <router-link to="/portfolio/three">
        <img src="../assets/arrow-down.svg" alt="arrow down" class="arrow arrow-down">
      </router-link>
    </div>
    <div class="right-content img2">

    </div>
  </div>
</template>

<script>
export default {
  name: 'two'
}
</script>

<style lang="scss" scoped>
  $page_color: #48B886;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/phone.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }

</style>

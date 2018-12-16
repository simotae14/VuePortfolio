<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>
        About me
      </h1>
      <p class="subtext">
        I design, code, and teach a bunch of other people to do the same.
      </p>
      <button>
        <router-link to="/portfolio/one">
          Look at my work
        </router-link>
      </button>
    </div>
    <div class="right-content">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, commodi quidem fuga enim illo explicabo! Maxime et consequatur laborum doloribus unde alias dignissimos iste hic! Eos ea repudiandae qui quia.
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolorem dignissimos incidunt harum ut illo aliquam eum, animi libero aperiam fugiat voluptate obcaecati accusantium pariatur consequuntur odio, saepe explicabo accusamus sequi?
      </p>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel, commodi quidem fuga enim illo explicabo! Maxime et consequatur laborum doloribus unde alias dignissimos iste hic! Eos ea repudiandae qui quia.
      </p>
    </div>
  </div>
</template>
<style lang="scss" scoped>
  .left-content {
    background-color: #ffe476;
  }

  .right-content {
    background: #fff;
    padding: 50px;
    margin-top: 80px;
    display: block;
  }

  button {
    font-size: 1.5em;
    margin-top: 100px;
  }

  .subtext {
    font-size: 1.5em;
    margin-top: 30px;
  }
</style>

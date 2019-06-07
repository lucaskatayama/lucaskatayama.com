<template>
  <section class="section">
    <header>
      $ find . -name "*lucas*"
      <small>
        Hey, if you want to find me and connect, here some places
      </small>
    </header>
    <div>
      <p class="social-buttons">
        <a href="https://www.linkedin.com/in/lucaskatayama" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-linkedin-square"></i>
        </a>
        <a href="https://github.com/lucaskatayama" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-github"></i>
        </a>
        <a href="https://twitter.com/@lucaskatayama" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-twitter"></i>
        </a>
        <a href="https://medium.lucaskatayama.com" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-medium"></i>
        </a>
        <a href="https://stackoverflow.com/users/1181036/lucas-katayama" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-stack-overflow"></i>
        </a>
        <a href="https://instagram.com/bylucask" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-instagram"></i>
        </a>
        <a href="https://facebook.com/lucaskatayamaphotos" target="_blank" class="btn btn-default btn-lg">
          <i class="fa fa-5x fa-facebook-square"></i>
        </a>
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "FindMe"
};
</script>

<style lang="scss" scoped>
section {
  div {
    text-align: center;
    margin: 0 auto;
  }
  .social-buttons {
    text-align: center;
    .btn {
      color: #555;
      margin: 0 1vw;

      &:hover {
        color: #3179c2;
      }
    }
  }
}
</style>

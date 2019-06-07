<template>
  <section class="intro">
    <div class="ping">Hello World!</div>
    <img data-v-75db5c58="" src="https://www.gravatar.com/avatar/54d4074475d7e585e2d7bba4ebe92525.jpg?size=400" class="avatar img-circle">
    <div class="name">Lucas Katayama</div>
  </section>
</template>

<script>
export default {
  name: "Intro"
};
</script>

<style lang="scss" scoped>
.intro {
  height: 100vh;
  display: flex;
  align-content: center;
  justify-content: center;
  flex-direction: column;
  text-align: center;
  color: white;
  font-weight: bold;
  font-size: 5em;
  .ping {
    font: italic 0.5em "Fira Mono", monospaced;
  }
  .avatar {
    text-align: center;
    width: 150px;
    border-radius: 50%;
    margin: 0 auto;
  }

  &::before {
    content: "";
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    z-index: -1000;
    background-size: cover;
    background-color: transparent;
    background-color: #000 !important;
    background-image: url("~@/assets/bg-intro.jpg");
    background-attachment: fixed;
    background-position: center;
  }
}
</style>

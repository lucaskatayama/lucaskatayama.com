<template>
  <div class="image">
    <a :href="photo.instagramUrl" target="_blank">
      <div :style="{backgroundImage: `url('${photo.photoUrl}')`}" class="photo" ></div>

      <span class="title">
          [ {{photo.title}} ]
      </span>
    </a>
  </div>
</template>

<script>
export default {
  name: "PhotoImage",
  props: ["photo"]
};
</script>

<style lang="scss" scoped>
.image {
  margin: 0.1% 0.3%;
  position: relative;
  display: inline-block;
  max-width: 100%;
  width: 100vw;
  height: 100vw;
  @media screen and (min-width: 1024px) {
    max-width: 20%;
    width: 18vmax;
    height: 18vmax;
  }
  @media screen and (min-width: 800px) and (max-width: 1024px) {
    width: 40vw;
    height: 40vw;
    max-width: 48%;
  }

  .photo {
    background-position: center center;
    background-size: cover;
    height: 100%;
    width: 100%;
  }

  .title {
    display: none;
  }

  &:hover {
    .photo {
      filter: grayscale(100%);
      opacity: 0.15;
      transition: 0.5s;
    }
    .title {
      position: absolute;
      display: block;
      width: 100%;
      z-index: 1000;
      color: black;
      text-transform: uppercase;
      height: 100%;
      text-align: center;
      top: 50%;
      @media screen and (min-width: 1024px) {
        font-size: 1em;
      }
      @media screen and (min-width: 800px) and (max-width: 1024px) {
        font-size: 1em;
      }
    }
  }
}
</style>

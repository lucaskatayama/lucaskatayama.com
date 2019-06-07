<template>
  <div class="work">
    <div class="content">
      <p class="title">{{work.title}}</p>
      <span class="description">
        {{work.description}}
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: "WorkItem",
  props: ["work"]
};
</script>

<style lang="scss" scoped>
.work {
  display: flex;
  width: 100%;
  justify-content: space-around;
  .img {
    text-align: center;
    max-width: 20%;
    display: inline;
    img {
      max-height: 100%;
      max-width: 100%;
    }
  }
  .content {
    width: 75%;
    .title {
      font-weight: bold;
      font-size: 1.5em;
    }
    .description {
    }
  }
}
</style>

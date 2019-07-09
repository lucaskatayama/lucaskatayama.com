<template>
  <div class="app">
    <div class="container-wrapper">
      <div class="container">
        <Home />
      </div>

    </div>
  </div>
</template>
<script>
import Home from "@/views/Home.vue";
export default {
  components: {
    Home
  }
};
</script>

<style lang="scss">
html,
body {
  margin: 0;
  background-color: #fff;
}

body {
  height: 100vh;
}

.app {
  font-family: "Zilla Slab", serif;
  font-size: 2em;
  color: #2c3e50e1;
  display: flex;
  height: 100%;
  flex-direction: column;
  justify-content: center;
  .container-wrapper {
    padding: 0 10vw;
    flex-direction: column;
  }
}
</style>

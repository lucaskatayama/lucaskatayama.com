<template>
  <div id="app">
    <intro></intro>
    <who-am-i></who-am-i>
    <find-me class="bg-grey"></find-me>
    <work></work>
    <photography class="bg-grey"></photography>
  </div>
</template>

<script>
import Intro from "./views/Intro";
import Work from "./views/Work";
import Photography from "./views/Photography";
import WhoAmI from "./views/WhoAmI";
import FindMe from "@/views/FindMe";

export default {
  name: "app",
  components: {
    Intro,
    Work,
    Photography,
    WhoAmI,
    FindMe
  },
  data() {
    return {
      sliderConfig: ["intro", "work"]
    };
  }
};
</script>
<style lang="scss">
* {
  font-family: "Zilla Slab";
  font-size: 1.04em;
}
html,
body {
  color: #333;
  margin: 0;
  padding: 0;
  font-family: "Zilla Slab";
  a {
    color: #3175bf;
  }
}
#app {
  padding: 0;
  width: 100%;
  margin: 0 auto;
}

.section {
  padding: 2em;
  margin-bottom: 2vw;
  header {
    font-size: 2em;
    font-family: "Fira Mono", monospaced;
    text-align: center;
    padding: 0 1em 1em 1em;
    small {
      display: block;
      font-size: 0.5em;
    }
  }
}

code {
  color: red;
  font-size: inherit;
  font-family: "Fira Mono", monospaced;
}

.bg-grey {
  background-color: #eeee;
}
</style>

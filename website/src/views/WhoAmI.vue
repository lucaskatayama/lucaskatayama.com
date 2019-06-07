<template>
  <section class="section">
    <header>$ whoami</header>
    <div>
      <code>
      <p>
        My name is Lucas Katayama and I am Brazilian Software Developer, with 5 years of experience building web and mobile applications, willing to move abroad to improve my skills in development.
      </p>
      <p>
        I am self-taught and I &#10084; new technologies and photography.
      </p>
      <p>
        Here is my
        <a target="_blank" href="https://files.lucaskatayama.com/cv.pdf?utm_source=homepage&amp;utm_campaign=resume&amp;utm_medium=link&amp;utm_term=resume&amp;utm_content=resume">résumé</a>.
      </p>
      <p>
        Or you can check my
        <a target="_blank" href="http://stackoverflow.com/story/lucaskatayama?utm_source=homepage&amp;utm_campaign=devstory&amp;utm_medium=link&amp;utm_term=devstory&amp;utm_content=devstory">Developer Story.</a></p>
      </code>
    </div>
  </section>
</template>

<script>
export default {
  name: "WhoAmI"
};
</script>

<style lang="scss" scoped>
.section {
  code {
    color: black;
    font-size: 1.2em;
  }
  margin: 0 auto;
  width: 50vw;
}
</style>

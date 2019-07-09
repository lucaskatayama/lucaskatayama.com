<template>
  <div class="home">
    <h1>Hello World!</h1>
    <h2>My name is Lucas Katayama</h2>
    <section>
      <p>
        and I am Brazilian Software Developer, building web and mobile
        applications, <br />
        with 5 years of experience willing to move abroad to improve my skills
        in development.
      </p>

      <p>I am self-taught and I ❤ new technologies and photography.</p>
    </section>
    <section class="links">
      <div class="links">
        <template v-for="link in links">
          <a target="_blank" :href="link.link" :key="link.label">{{
            link.label
          }}</a>&nbsp;
        </template>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  data() {
    return {
      links: [
        {
          link:
            "https://files.lucaskatayama.com/cv.pdf?utm_source=homepage&utm_campaign=resume&utm_medium=link&utm_term=resume&utm_content=resume",
          label: "résumé"
        },
        {
          link: "https://www.linkedin.com/in/lucaskatayama",
          label: "linkedin"
        },
        {
          link: "https://github.com/lucaskatayama",
          label: "github"
        },
        {
          link: "https://twitter.com/@lucaskatayama",
          label: "twitter"
        },
        {
          link: "https://medium.lucaskatayama.com",
          label: "medium"
        },
        {
          link: "https://stackoverflow.com/users/1181036/lucas-katayama",
          label: "stack overflow"
        },
        {
          link: "https://instagram.com/bylucask",
          label: "instagram"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
$color-link: #3175bf;
section {
  margin-bottom: 2em;
  &.links {
    font-size: 0.8em;
    a {
      color: $color-link;
      text-transform: lowercase;
    }
  }
}
</style>

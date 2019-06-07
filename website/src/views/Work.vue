<template>
  <section class="section">
    <header>
      $ ps aux | grep lucas
      <small>
        What I've been doing
      </small>
    </header>
    <work-item v-for="(work, $index) in works"
               :key="$index"
               :work="work"></work-item>
  </section>
</template>

<script>
import WorkItem from "@/components/work-item";

export default {
  name: "Work",
  components: {
    WorkItem
  },
  data() {
    return {
      works: [
        {
          title: "Loren Ipsum",
          description:
            "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean non molestie urna. In vel erat massa. Quisque rhoncus hendrerit faucibus. Aliquam varius lobortis lacus quis faucibus. Nunc eu est ut tellus facilisis laoreet. Nam vel est facilisis, pharetra nisi vitae, maximus nibh. Donec accumsan, est tincidunt pulvinar vehicula, libero urna elementum elit, quis facilisis tortor enim nec arcu. Nam tortor neque, euismod eget egestas ut, iaculis ut tellus. Integer vulputate fermentum dolor ut tempor. Praesent eu interdum est. Ut vehicula est ut ipsum vestibulum, quis tristique lorem placerat. Suspendisse sodales mauris vel augue bibendum consectetur. Vestibulum ullamcorper enim eget vehicula vehicula. Phasellus fermentum volutpat ultricies. Proin id diam urna."
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
</style>

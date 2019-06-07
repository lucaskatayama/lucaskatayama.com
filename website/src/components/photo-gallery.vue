<template>
  <div class="images">
    <photo-image
      v-for="(photo, $index) in photos"
      :key="$index"
      :photo="photo"
    ></photo-image>
  </div>
</template>

<script>
import PhotoImage from "@/components/photo-image";

export default {
  components: {
    PhotoImage
  },
  props: ["photos"]
};
</script>

<style lang="scss" scoped>
.images {
  // float: left;
  text-align: center;
}
</style>

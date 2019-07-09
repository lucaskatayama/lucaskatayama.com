<template>
  <section class="section">
    <header>
      $ cd $HOME/Pictures && ls
      <small>Another part of my life</small>
    </header>
    <div class="content">
      <photo-gallery :photos="photos"></photo-gallery>
    </div>
  </section>
</template>

<script>
import PhotoGallery from "@/components/photo-gallery";

export default {
  name: "Photography",
  components: {
    PhotoGallery
  },
  data() {
    return {
      photos: [
        {
          title: "Chile - Santiago",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/86c0e8f3f58c8e6a42272ce78cbfeb9e/5C995ED9/t51.2885-15/sh0.08/e35/p640x640/42112229_1985105281780712_3184949408845500753_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BoneUIwheNv/"
        },
        {
          title: "Chile - Santiago",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/afbae038b9baed0d8f79f69edb3d38a3/5C9D3886/t51.2885-15/sh0.08/e35/s640x640/41698877_172536817004149_1950740144750630822_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BodSrMXB6Ul/"
        },
        {
          title: "Brazil - Itatiaia National Park",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/15d51f4f5efd58298e16d4c80ac6caf8/5C8C6258/t51.2885-15/sh0.08/e35/s640x640/36149025_1968265456526697_3158319589981421568_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BknJJ6IAYbP/"
        },
        {
          title: "Brazil - Itatiaia National Park",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/497353829a0899f6bec68b15f2b4bf85/5C9F7A18/t51.2885-15/sh0.08/e35/s640x640/34982942_173165760205259_5900751865989038080_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BkMKEV1BdhN/"
        },
        {
          title: "Flora Shapes",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/29c973fc6e2cec8646e6c8a16e27eed0/5CA9ADB5/t51.2885-15/sh0.08/e35/s640x640/15305906_1865947523639285_5421374550149431296_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BN690HUBgMG/"
        },
        {
          title: "Brazil - Itatiaia National Park",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/efa3c4b09105591faa661705c4a2d167/5CA183CF/t51.2885-15/sh0.08/e35/s640x640/35001516_432888783840800_6395769588704870400_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BkQ5bK1BHJs/"
        },
        {
          title: "Brazil - Itatiaia National Park",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/5656bde27021f4a504e7c0cbe1b66f4b/5CAF0A45/t51.2885-15/sh0.08/e35/s640x640/35459642_1364067680360146_4513027389822861312_n.jpg?_nc_ht=instagram.fcpq6-1.fna.fbcdn.net",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BkXvbqDBgtA/"
        },
        {
          title: "Brazil - Itatiaia National Park",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/3d4b8e43ac9807c6c9762641103f081a/5C9C6FB8/t51.2885-15/sh0.08/e35/s640x640/35459460_371895663333385_2619634007054221312_n.jpg",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BkpwD2fDVDd/"
        },
        {
          title: "Chile - Santiago",
          photoUrl:
            "https://instagram.fcpq6-1.fna.fbcdn.net/vp/cc43a438df9f18b8f2e25bee08d79f1d/5C9B375B/t51.2885-15/sh0.08/e35/s640x640/37905047_825967440944838_8537621044226162688_n.jpg?_nc_ht=instagram.fcpq6-1.fna.fbcdn.net",
          alt: "",
          instagramUrl: "https://www.instagram.com/p/BmCo2oBhs-p"
        }
      ]
    };
  }
};
</script>

<style lang="scss" scoped>
.content {
  display: inline-block;
}
</style>

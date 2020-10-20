<template>
  <image-box images-list-class="flex" :images="images"></image-box>
</template>

<script>
import { defineComponent } from "vue";
import ImageBox from "./components/ImageBox";

export default defineComponent({
  name: "App",
  components: {
    ImageBox,
  },
  setup() {
    const images = [
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15D8R8-1527377973_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15D8R8-1527377973_680x0.jpg",
        caption: "1",
      },
      {
        thumb:
          "https://s3-us-west-1.amazonaws.com/powr/defaults/image-slider2.jpg",
        src:
          "https://s3-us-west-1.amazonaws.com/powr/defaults/image-slider2.jpg",
        caption: "2",
      },
      {
        thumb:
          "https://i-kinhdoanh.vnecdn.net/2018/06/18/1-1529296929_680x0.jpg",
        src:
          "https://i-kinhdoanh.vnecdn.net/2018/06/18/1-1529296929_680x0.jpg",
        caption: "3",
      },
      {
        thumb:
          "http://127.0.0.1:4567/lin-test/public/5oQeGbjGqw2njkADPBl2FOx256X9NqiRkgY1AXNE.jpeg",
        src:
          "http://127.0.0.1:4567/lin-test/public/FHkGOEj6SmyWlPSsS82KLNoCeWaygJsfHQcp83At.jpeg",
        caption: "4",
      },
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/775162441-MR-2031-8E033EFCEBB928DC12A2A0AA3CEC4C33-21885-1527376486_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/775162441-MR-2031-8E033EFCEBB928DC12A2A0AA3CEC4C33-21885-1527376486_680x0.jpg",
        caption: "5",
      },
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15E0DG-1527379049_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15E0DG-1527379049_680x0.jpg",
        caption: "6",
      },
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15D8R8-1527377973_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15D8R8-1527377973_680x0.jpg",
        caption: "7",
      },
      {
        thumb:
          "https://s3-us-west-1.amazonaws.com/powr/defaults/image-slider2.jpg",
        src:
          "https://s3-us-west-1.amazonaws.com/powr/defaults/image-slider2.jpg",
        caption: "8",
      },
      {
        thumb:
          "https://i-kinhdoanh.vnecdn.net/2018/06/18/1-1529296929_680x0.jpg",
        src:
          "https://i-kinhdoanh.vnecdn.net/2018/06/18/1-1529296929_680x0.jpg",
        caption: "9",
      },
      {
        thumb:
          "http://127.0.0.1:4567/lin-test/public/5oQeGbjGqw2njkADPBl2FOx256X9NqiRkgY1AXNE.jpeg",
        src:
          "http://127.0.0.1:4567/lin-test/public/FHkGOEj6SmyWlPSsS82KLNoCeWaygJsfHQcp83At.jpeg",
        caption: "10",
      },
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/775162441-MR-2031-8E033EFCEBB928DC12A2A0AA3CEC4C33-21885-1527376486_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/775162441-MR-2031-8E033EFCEBB928DC12A2A0AA3CEC4C33-21885-1527376486_680x0.jpg",
        caption: "11",
      },
      {
        thumb:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15E0DG-1527379049_680x0.jpg",
        src:
          "https://i-thethao.vnecdn.net/2018/05/27/000-15E0DG-1527379049_680x0.jpg",
        caption: "12",
      },
    ];

    return {
      images,
    };
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.flex {
  display: flex;
  width: 100%;
}

.flex img{
  max-width: 100px;
}
</style>

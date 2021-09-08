<template>
  <div class="container">
    <splide :options="options">
      <splide-slide>
        <img src="../../assets/construction-machine-3412240_1920.jpg" />
      </splide-slide>
      <splide-slide>
        <img src="../../assets/construction-site-1359136_1920.jpg" />
      </splide-slide>
      <splide-slide>
        <img src="../../assets/excavator-1212472_1920.jpg" />
      </splide-slide>
      <splide-slide>
        <img src="../../assets/welder-3018425_1920.jpg" />
      </splide-slide>
      <splide-slide>
        <img src="../../assets/excavator-1212472_1920.jpg" />
      </splide-slide>
    </splide>
  </div>
</template>

<script>
// import splide
import { Splide, SplideSlide } from "@splidejs/vue-splide";
// splide css
import "@splidejs/splide/dist/css/themes/splide-skyblue.min.css";
export default {
  components: {
    Splide,
    SplideSlide,
  },
  data() {
    return {
      options: {
        rewind: true,
        width: 1000,
        perPage: 4,
        gap: "1rem",
        fixedHeight: 110,
        cover: true,
        focus: "center",
      },
    };
  },
};
</script>

<style>
</style>
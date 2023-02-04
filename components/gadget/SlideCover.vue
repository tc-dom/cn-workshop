<template>
  <div class="cover_scope">
    <div class="overlay_cover"></div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="rgba(31, 30, 25, 1)"
      img-width="1024"
      img-height="300"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <b-carousel-slide>
        <template #img>
          <img
            class="cover_sli_img"
            width="1024"
            height="300"
            src="https://media.kkpfg.com/image/2018/Sep/Phatra-GNP_Web-1620x540.jpg"
            alt="image slot"
          />
        </template>
      </b-carousel-slide>

      <!-- Slide with blank fluid image to maintain slide aspect ratio -->
    </b-carousel>

    <MainButton />
  </div>
</template>

<script>
import MainButton from "~/components/gadget/MainButton.vue";
export default {
  components: {
    MainButton,
  },
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>

<style>
.cover_scope {
  position: relative;
  height: 470px;
  background: rgba(31, 30, 25, 1);
}
.overlay_cover {
  position: absolute;
  top: 0px;
  width: 100%;
  height: 70px;

  background-image: linear-gradient(
    to bottom,
    rgba(31, 30, 25, 1),
    rgba(255, 255, 255, 0)
  );
  z-index: 1;
}


.cover_scope .carousel-control-prev-icon {
    width: 40px;
    height: 40px;
    background-image: url('/arrow.svg');
    transform: rotate(180deg);
    border: 1px solid#fff;
    background-size: 60%;
    border-radius: 50%;
    padding: 30px;
       margin-top: -20%;
    margin-left: -80px;
}
 
.cover_scope .carousel-control-next-icon {
    width: 40px;
    height: 40px;
   background-image: url('/arrow.svg');
       border: 1px solid#fff;
    background-size: 60%;
    border-radius: 50%;
    padding: 30px;
    margin-top: -20%;
    margin-left: 80px;
}


.cover_scope img {
  height: 80%;
}
.cover_sli_img {
  width: 90%;
  height: 90%;
  margin: auto;
  display: block;
  object-fit: cover;
}
</style>

<template>
  <div class="cover_scope">
    <div class="overlay_cover"></div>
    <div class="image_cover">
      <img src="/cover.jpeg" alt="" srcset="">
    </div>
    <div class="btn_cover">
      <button class="btn_cover_back_button idx"></button>
    </div>
    <div class="btn_cover" style="right:0;">
      <button class="btn_cover_next_button idx"></button>
    </div>

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
  background: rgba(31, 30, 25, 1) ;
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

.image_cover {
  width: 100%;
  height: auto;
  background: rgba(31, 30, 25, 1);
  display: block;
  margin: auto;
  
}
.image_cover img{
  width: 100%;
  display: block;
  height: 100%;
  object-fit: cover;
}
.btn_cover {
  width: 10%;
  height: 70px;
  position: absolute;
  top: 175px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.idx {
  width: 65px;
  border-radius: 50%;
  height: 65px;
  background-repeat: no-repeat;
  border: none;
  background-color: rgba(255, 255, 255, 0);
}
.btn_cover_back_button {
  background-image: url("/slide/slide-left.png");
  background-position-x: -10px;
  background-position-y: -15px;
  background-size: 138%;
}
.btn_cover_next_button {
  background-image: url("/slide/slide-right-hover.png");
  background-position-x: -14px;
  background-position-y: -9px;
  background-size: 138%;
}
</style>

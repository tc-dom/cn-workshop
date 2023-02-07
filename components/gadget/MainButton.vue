<template>
  <div class="main_btn">
    <button class="step_btn">
      <img src="/bt-back@2x.png" alt="" srcset="">
    </button>
    <b-button squared class="active_btn">
      <div class="overlay_btn"></div>
      <span>About Us</span></b-button
    >
    <b-button squared>
      <div class="overlay_btn"></div>
      <span>Awords</span></b-button
    >
    <b-button squared>
      <div class="overlay_btn"></div>
      <span>Our Businesses</span></b-button
    >
    <b-button squared>
      <div class="overlay_btn"></div>
      <span>News&Activities</span></b-button
    >
        <button class="step_btn">
      <img src="/bt-next@2x.png" alt="" srcset="">
    </button>
  </div>
</template>
[]
<style>
.step_btn{
  background: none !important;
  width: 30px !important;
  height: 30px !important;
  display: flex;
  margin-right:29px !important;
 margin-left:29px !important;
}
.step_btn img{
  width: 18px !important;
  height: 30px;
  margin:auto;
}
.main_btn {
  display: flex;
  width: 96%;
  max-width: 1245px;
  right: 0;
  justify-content: space-between;
  align-items: center;
  left: 0;
  margin: -30px auto 0px auto;
  height: 90px;
  z-index: 2;
  position: absolute;
  bottom: -60px;
  text-align: center;
}
.main_btn button {
  height: 86px;
  position: relative;
  font-family: "Kanit", sans-serif;
  font-size: 20px !important;
  font-weight: 500 !important;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.5;
  letter-spacing: normal;
  margin: 2.5px;

  width: 262px;
  border: none;
  color: rgba(101, 92, 159, 1);
  text-align: left;
  background-image: linear-gradient(to left, #655a9f, #8b8bc1);
}
.overlay_btn {
  position: absolute;
  width: 100%;
  height: 93%;
  top: 0;
  left: 0;
  background: #e8e7ec;
}
.main_btn span {
  z-index: 1;

  top: 35%;
  left: 20px;
  position: absolute;
}
.main_btn button:hover .overlay_btn {
  transform: 0.5s;
  height: 0px;
}
.active_btn .overlay_btn {
  height: 0px;
}
.active_btn {
  color: #fff !important;
}
</style>

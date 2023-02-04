<template>
  <div class="main_btn">
    <b-button squared class="active_btn">
        <div class="overlay_btn"></div>
        <span>About Us</span></b-button>

            <b-button squared>
        <div class="overlay_btn"></div>
        <span>Awords</span></b-button>
             <b-button squared>
        <div class="overlay_btn"></div>
        <span>Our Businesses</span></b-button>
             <b-button squared>
        <div class="overlay_btn"></div>
        <span>News&Activities</span></b-button>

  
  </div>
</template>
[]
<style>
.main_btn {
  display: block;
  width: 96%;
  right: 0;
  left: 0;
  margin: -30px auto 0px auto;
  height: 90px;
  z-index: 2;
  position: absolute;
  bottom: -60px;
  text-align: center;
}
.main_btn button {
  height: 90px;
  position: relative;
    font-size: 18px;
    font-weight: bold;
    margin: 2.5px;
  width: 20%;
      border:none;
      color: rgba(101, 92, 159, 1);
  text-align: left;
  background: rgb(141, 138, 192);
  background: linear-gradient(
    90deg,
    rgba(141, 138, 192, 1) 0%,
    rgba(101, 92, 159, 1) 100%
  );
}
.overlay_btn{
    position: absolute;
    width: 100%;
    height: 93%;
    top: 0;
    left: 0;
    background: #e8e7ec;
}
.main_btn span{
    z-index: 1;
 
    top: 35%;
    left: 20px;
     position: absolute;
}
.main_btn button:hover .overlay_btn{

    transform: .5s;
        height: 0px;
}
.active_btn .overlay_btn{
    height: 0px; 
}
.active_btn{
    color: #fff !important;
}
</style>

<template>
     <div class="crack_container media_zone">
       <div class="media_heading">
         <span class="datt"></span>
        <h2>KKP Channel</h2>
        <span style="color: #999;">
            อัพเดตทุกความรู้ด้านการเงินและการลงทุนก่อนใคร พร้อมอินเทรนต์ไปกับหลายเรื่องราวไลฟ์สไตล์
        </span>
    
       </div>

    <div class="container">
          <nav class="kkp_nav">
        <a class="kkp_nav_active" aria-current="page" href="#">KKP FOCUS</a> <span>|</span>
        <a  href="#">OPTIMISE</a><span>|</span>
        <a  href="#">KKP ADVISOR</a>
      
      </nav>
          <div class="mb-3">
        <div class="media-control">
         
            <div class="main-media-zone">
               <img src="/cover-video.png" alt="" srcset="">
            </div>
         
          <div class="media-card">
            <div class="media-body">
              <h1 class="media-title">KKP Focus</h1>
              <p class="media-text">
                ฝนนักสู้ พบเรื่องราวจริง เจ็บจริง ประสบความสำเร็จจริง ที่จะเป็นแรงกระตุ้นให้ SME นักสู้รุ่นต่อไป 
ได้ก้าวไปถึงฝัน
              </p>
              
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
</template>



<style >
.media-control{
    display: flex;
    flex-direction: row;
    align-items: center;

}
.media_zone{
    margin-top: 40px;
   
}
.kkp_nav{
    color: #999;
    display: block;
    margin-bottom: 20px;
}
.kkp_nav a{
    color: #999;
}
.kkp_nav_active{
    color: #000 !important;
}
.kkp_nav span{
    display: inline-block;
    margin: 0px 20px;
}
.media-card{
    margin: 40px;
}
.main-media-zone{
    flex-shrink: 0;
    max-width: 720px;
    width: 100%;
    height: 414px;
    background: #000;
    box-shadow: 8px 10px 23px -10px rgba(0,0,0,0.75);
-webkit-box-shadow: 8px 10px 23px -10px rgba(0,0,0,0.75);
-moz-box-shadow: 8px 10px 23px -10px rgba(0,0,0,0.75);
}
.media_heading{
        display: flex;
        align-items: center;
        margin-top: 60px;
        margin-bottom: 60px;
}
.media_heading h2{
    margin-left: 10px;
    margin-right: 20px;
  font-size: 42px;
  font-weight: 500;

  color: #594f74;
}
.media-title{
      color: rgba(101, 92, 159, 1);
      font-weight: 600;
      font-family: 'kanit',sans-serif;
    margin-bottom: 20px;
    
}
.media-body{
    display: block;
    padding:70px 0px;
    border-width: 3px;
    border-top: 3px;
    max-width: 276px;
    border-left: 0px;
    border-right: 0px;
    border-bottom: 3px;
  border-style: solid;
  border-image: linear-gradient(to right, #d0cfd8 -3%, #e9eaef 55%, #b9b9c3 111%) 1;

}
.media-text{
     font-family: 'Kanit',sans-serif;
  font-size: 20px;
font-weight: 400;
  line-height: 1.4;
  letter-spacing: normal;
  color: #84848f;
}
.datt{
    display: block;
    width: 60px;
    height: 3px;
    background: #999;
}


@media screen and (max-width: 1000px) {
  .media-control{
    flex-direction: column;
  }

}


</style>
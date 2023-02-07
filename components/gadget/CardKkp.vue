<template>
     <div class="crack_container">
               <div class="cn_workshop_nav">
            <a href="#"></a>

            <button>
              ดูทั้งหมด
              <span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="18"
                fill="#999"
                height="18"
                viewBox="0 0 24 24"
              >
                <polygon
                  points="7.293 4.707 14.586 12 7.293 19.293 8.707 20.707 17.414 12 8.707 3.293 7.293 4.707"
                />
              </svg>
              </span>
            </button>
          </div>
      <div class="row">
        <div class="col-4">
          <div class="card_kkp">
            <div class="card_kkp-img">
                   <img src="/clip/clip-1.png"  alt="..." />
         
            </div>
            <div class="card_kkp-body">
              <p class="card_kkp-text">KKP Focus ช่วงที่ 2 กูรู... โต๊ะกลม</p>
           
            </div>
          </div>
        </div>

         <div class="col-4">
          <div class="card_kkp">
            <div class="card_kkp-img">
        <img src="/clip/clip-2.png"  alt="..." />
            </div>
            <div class="card_kkp-body">
              <p class="card_kkp-text">KKP Focus ช่วงที่ 1 ย่อประเด็นโลก โยกประเด็นร้อน</p>
           
            </div>
          </div>
        </div>

         <div class="col-4">
          <div class="card_kkp">
            <div class="card_kkp-img">
                <img src="/clip/clip-3.png"  alt="..." />
            </div>
            <div class="card_kkp-body">
              <p class="card_kkp-text">KKP Focus ช่วงที่ 2 กูรู... โต๊ะกลม</p>
           
            </div>
          </div>
        </div>
      </div>

      <div class="slide_stats">
        <span class="slide_stats_active"></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </div>
</template>

<style >

.card_kkp-body{
  margin: 20px 0px;
}
.card_kkp-text{
  font-size: 24px;
  font-weight: blod;
  color: rgba(101, 92, 159, 1);
  font-family: 'kanit',sans-serif;
}
.card_kkp-img{
  width: 100%;
  height: auto;
  max-height: 220px;
}
.card_kkp-img img{
  width: 100%;
  height: 100%;
  object-fit: cover;
}

</style>
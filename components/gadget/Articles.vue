<template>
  <div class="crack_container" style="margin-top: 120px">
    <div class="row">
      <div class="col-8">
        <div class="cn_workshop_nav">
          <a href="#">Articles</a>

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
        <div class="mb-3">
         <div class="card-article">
             <div class="row g-0">
            <div class="col-md-7">
                <div class="card-article-img">
                     <img
                src="https://media.kkpfg.com/image/2022/Nov/checklist-for-2nd-hand-real-estate_628x443.jpg"
                class="img-fluid rounded-start"
                alt="..."
              />
                </div>
             
            </div>
            <div class="col-md-5">
              <div class="card-article-body">
                <h5 class="card-article-title">
                  Margin of safety กลยุทธ์การลงทุนอย่างปลอดภัย
                  หลักการลงทุนของเบนจามินเกรแฮม
                </h5>
                <p class="card-article-text">
                  ตอบคำถามที่ว่า คุณมีความจำเป็นพร้อมเป็นเจ้าของหรือยัง เช่น
                  เพื่อหน้าที่การงาน อาชีพ หรือการเดินทาง
                  เพราะการซื้อรถนอกจากซื้อรถแล้ว ยังมีค่าน้ำมัน ค่าบำรุงรักษา
                  ค่าประกันภัย ซึ่งเป็นค่าใช้จ่ายในระยะยาว
                </p>
                <p class="card-article-category">
                การลงทุน
                </p>
              </div>
            </div>
          </div>
         </div>
        </div>
      </div>
      <div class="col-4">
        <div class="cn_workshop_nav">
          <a href="#">News</a>

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

        <side-slide/>


      </div>
    </div>

    <div class="row">
      <div class="col-4" v-for="i in 2" :key="i">
        <div class="card-article">
        <div class="card-article-img">
              <img
            src="https://thaipublica.org/wp-content/uploads/2016/02/Phatra-Edge-1-email-scaled.jpg"
            class="card-img-top"
            alt="..."
          />
        </div>
           <div class="card-article-body">
                <h5 class="card-article-title">
                  จับจังหวะการลงทุนเป็นเงินล้านง่ายๆ ใกล้แค่เอืื้อ
                </h5>
               
                <p class="card-article-category">
                การลงทุน
                </p>
              </div>
       
        </div>
      </div>
      <div class="col-4">
       <div class="card bg-white p-4 ">
        <h2>Set Index</h2>
        <p> <iframe src="https://weblink.settrade.com/banner/banner3.jsp" width="200" height="260" frameborder="0" scrolling="no"></iframe></p>
       </div>
      </div>
    </div>
  </div>
</template>

<script>
import SideSlide from "~/components/gadget/SideSlide.vue";

export default {
  components: { SideSlide },

};
</script>

<style>
.card-article{
    margin-top: 20px;
    margin-bottom: 20px;
}
.card-article-img{
    margin-bottom: 20px;
}
.card-article-title{
     font-size: 24px;
    margin-bottom: 20px;
    line-height: 35px;
  color: rgba(101, 92, 159, 1);
  font-family: 'kanit',sans-serif;
}
.card-article-text{
    font-size: 17px;
    color: #999;
}
.card-article-category{
    font-size: 13px;
   color: rgba(101, 92, 159, 1);
    border-left: 3px solid rgba(101, 92, 159, 1);
    padding-left: 10px;
}
</style>

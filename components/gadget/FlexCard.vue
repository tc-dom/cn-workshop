<template>
   <div class="flex_card">
          <div class="flex_card_cover">
             <img
              src="/article/img-article-1.png"
              class="card-img-top"
              alt="..."
            />
          </div>
          <div class="flex_card_detail">
            <div class="flex_card_detail_title">
                Margin of Safety กลยุทธ์การลงทุนอย่างปลอดภัย หลักการลงทุนของเบนจามิน เกรแฮม
            </div>
            <div class="flex_card_detail_content">
                ตอบคำถามที่ว่า คุณมีความจำเป็น พร้อมเป็นเจ้าของหรือยัง เช่น เพื่อหน้าที่การงาน อาชีพ หรือการเดินทาง ความสะดวกสบาย เพราะการซื้อรถนอกจากค่ารถแล้ว ยังมีค่าน้ำมัน ค่าบำรุงรักษา ค่าประกันภัย ซึ่งเป็นค่าใช้จ่ายในระยะยาว
            </div>
            <div class="flex_card_detail_category">
                การลงทุน
            </div>
          </div>
        </div>
</template>

<script>
export default {

}
</script>

<style>
.flex_card{
    width: 100%;
    display: flex;
    flex-direction: row;
}
.flex_card_cover{
    width: 100%;
    max-width: 428px;
    margin: auto;
    height: auto;
    flex-shrink: 0;
}
.flex_card_detail{
    width: 100%;
    padding: 0px 27px;
}
.flex_card_detail_title{
    font-family: 'Kanit',sans-serif;
  font-size: 24px;
  font-weight: 500;
  line-height: 1.25;
  color: #594f74;
}
.flex_card_detail_content{
     font-family: 'Tahoma',sans-serif;
  font-size: 16px;
  line-height: 1.5;
  color: #84848f;
  margin-top: 7px;
}
.flex_card_detail_category{
    display: block;
    border-left: 3px solid#635f98;
    margin-top: 34px;
    font-size: 14px;
    padding: 0px 10px;
  line-height: 1.71;
  color: #635f98;
}

@media screen and (max-width: 1000px) {
 .flex_card{
  
    flex-direction: column;
}

}
</style>
<template>
    <div class="mt-5">
      
      
         <footer class="footer-container">
     <div class="crack_container">
         <div class="row">
        <div class="col-4">
         <b-img class="footer_logo" src="/favicon.png" alt="Responsive image"></b-img>
         <div class="sub_footer_logo">
             <h2>บริษัท ทุนภัทร จำกัด (มหาชน)</h2>
          <p>
            ชั้น 9 อาคารสำนักงานเมืองไทย-ภัทร 1 252/6<br />
            ถนนรัชดาภิเษก แขวงห้วยขวาง<br />
            กรุงเทพมหานคร 10310
          </p>
         </div>
        </div>
       <div class="col-4 mt-4">
        <div class="row">
             <div class="col-6">
          <h3>เมนู</h3>
          <li>รู้จัก บลจ.ภัทร</li>
          <li>เกี่ยวกับเรา</li>
          <li>ติดต่อเรา</li>
          <li>คำถามที่พบบ่อย</li>
          <li>สมัครงาน</li>
          <li>Links</li>
        </div>
        <div class="col-6">
          <h3>เมนู</h3>
          <li>รู้จัก บลจ.ภัทร</li>
          <li>เกี่ยวกับเรา</li>
          <li>ติดต่อเรา</li>
          <li>คำถามที่พบบ่อย</li>
          <li>สมัครงาน</li>
          <li>Links</li>
        </div>
        </div>
       </div>
        <div class="col-4">
            <div class="ft_contact mt-4">
                         <h3>ติดต่อเรา</h3>
          <li>
            <img class="ico_contact" src="/p2.png" alt="" srcset="">
            (66) 2305 9800</li>
          <li>
             <img class="ico_contact" src="/p.png" alt="" srcset="">
             (66) 2305 9803</li>
          <li>
             <img class="ico_contact" src="/p3.png" alt="" srcset="">
             customerservice@phatraasset.com</li>
            </div>


            <div class="ft_socail">
                 <img class="ico_socail" src="/s1.png" alt="" srcset="">
                  <img class="ico_socail" src="/s3.png" alt="" srcset="">
                   <img class="ico_socail" src="/s2.png" alt="" srcset="">

            </div>
         
        </div>
      </div>
     </div>
      <div class="footer-center">
       <div class="crack_container">
         <div class="flex_items_direc">
            <div class="footer-center-links">
          <a href="#">แผนผังเว็บไซต์</a> <span>|</span> <a href="#">ข้อตกลงและเงื่อนไข</a> <span>|</span>
          <a href="#">นโยบายข้อมูลส่วนตัว</a>
        </div>
        <div>
          @2019 Phatra A@ สงวนลิขสิทธฺ์ 2562 บริษัทหลักทรัพย์การจัดการกองทุน
          ภัทร จำกัดssec All right reserved
        </div>
         </div>
       </div>
      </div>
    </footer>

    <div class="sub_bank_logo">
        <img class="sub_bank_logo_big" src="/bank_logo/1.png" alt="" srcset="">
        <img src="/bank_logo/2.png" alt="" srcset="">
        <img src="/bank_logo/2.png" alt="" srcset="">
        <img src="/bank_logo/2.png" alt="" srcset="">
    </div>
    </div>
</template>

<style>
.footer-container {
    color: #dcdcdc;
background: rgb(112,110,176);
background: linear-gradient(180deg, rgba(112,110,176,1) 0%, rgba(56,49,106,1) 100%);
  padding: 20px 0px;
  line-height: 30px;
     text-align: left;
}
.footer-container h2{
    font-size: 24px;
    font-family: 'kanit',sans-serif;
}

.footer-container h3{
    font-size: 20px;
    display: block;
    margin-bottom: 20px;
    font-family: 'kanit',sans-serif;
}
.footer-center{
    border-top: 1px solid#999;
}
.footer-center-links a{
    display: inline-block;
    color: #dcdcdc;
}
.footer-center-links span{
    margin:0px 15px;
    inherits: none;
}
.flex_items_direc{
        display: flex;
    flex-direction: row;
    justify-content: space-between;
    font-size: 13px;
    padding-top: 20px;
}
.footer-container li{
    list-style-type: none;
    font-size: 14px;
}
.ft_contact li{
    font-size: 18px !important;
}
.ico_contact{
    margin: 10px 10px 10px 0px;
    width: 28px;
    height: 28px;
}
.ft_socail{
    margin: 20px 0px;
    
}
.ico_socail{
    width: 45px;
    margin-right:5px ;
    height: 45px;
    border-radius: 50%;
}
.footer_logo{
    position: absolute;
    width: 240px;
    top: -60px;
}
.sub_footer_logo{
    margin-top: 130px;
}.sub_bank_logo{
    display: flex;
    justify-content: space-between;
    max-width: 1240px;
    margin: auto;
    padding: 20px 0px;
}
.sub_bank_logo img{
  
            opacity: .3;
    max-height: 50px;
    
}
.sub_bank_logo_big{
  
            opacity: .3;
    max-height: 60px !important;
    
}

</style>
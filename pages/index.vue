<template>
  <div>
    <navbar/>
    <slide-cover/>
    <div class="ar_bg">
      <articles/>
    </div>
    <media/>
    <card-kkp class="mt-5"/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from "~/components/template/Navbar.vue";
import SlideCover from "~/components/gadget/SlideCover.vue";
import CardKkp from "~/components/gadget/CardKkp.vue";
import Articles from "~/components/gadget/Articles.vue";
import Media from "~/components/gadget/Media.vue";
import Footer from "~/components/template/Footer.vue";

export default {
  components: { Navbar, SlideCover, Footer, CardKkp, Media, Articles },
  name: "IndexPage",
};
</script>

<style>
.ar_bg{
   height:1222px;
   position: relative;
   top: 0;
   margin-top: 0px;
   padding-top: 10px;
  width:100vw;
  background-image: url('/bg@2x.png');
  background-size:cover ;
}
* {
  font-family: "Tahoma", sans-serif;
  font-size: 16px;
  line-height: 1 .56;

}

.crack_container {
  max-width: 1240px;
  width: 100%;
  display: block;
  margin: auto;
  overflow: hidden;
}

.cn_workshop_nav {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 20px 0px;
}
.cn_workshop_nav button {
  border: none;
  padding: 0px;
  background: none;
  font-size: 13px;
  color: #999;
  display: flex;
  flex-direction: row;
  align-items: center;
}
.cn_workshop_nav span {
  display: inline-block;
  border: 1px solid#999;
  border-radius: 50%;
  padding: 2px;
  display: flex;
  margin-left: 10px;
  align-items: center;
}
.cn_workshop_nav a {
  font-size: 26px;
  font-weight: bold;
  color: rgba(101, 92, 159, 1);
}

.slide_stats_active {
  background: rgba(101, 92, 159, 1);
}
.slide_stats span {
  display: inline-block;
  width: 10px;
  margin: 2.5px;
  height: 10px;
  border: 1px solid #999;
  border-radius: 50%;
}
.slide_stats {
  display: block;
  margin: 20px;
  text-align: center;
}
</style>

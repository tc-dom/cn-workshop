<template>
  <div class="crack_container" style="margin-top: 120px">
    <div class="row">
      <div class="col-lg-8 col-md-8 col-sm-12">
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
        <div class="col-12 col-md-12 col-sm-12">
          <flex-card />
        </div>
      </div>
      <div class="col-3 col-md-4 col-sm-12">
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

        <side-slide />
      </div>
    </div>

    <div class="row">
      <div class="col-4 col-md-4 col-sm-12">
        <div class="card-article">
          <div class="card-article-img">
            <img
              src="/article/img-article-2.png"
              class="card-img-top"
              alt="..."
            />
          </div>
          <div class="card-article-body">
            <h5 class="card-article-title">
              จับจังหวะการลงทุนเป็นก็สร้างเงินล้านได้ง่ายๆใกล้แค่เอื้อม
            </h5>

            <p class="card-article-category">การลงทุน</p>
          </div>
        </div>
      </div>
      <div class="col-4 col-md-4 col-sm-12">
        <div class="card-article">
          <div class="card-article-img">
            <img
              src="/article/img-article-3.png"
              class="card-img-top"
              alt="..."
            />
          </div>
          <div class="card-article-body">
            <h5 class="card-article-title">
              Margin of Safety กลยุทธ์การลงทุนอย่างปลอดภัย Margin of Safety
            </h5>

            <p class="card-article-category">การลงทุน</p>
          </div>
        </div>
      </div>
      <div class="col-4">
        <div class="card bg-white p-4">
          <h2>Set Index</h2>
          <p>
            <iframe
              src="https://weblink.settrade.com/banner/banner3.jsp"
              width="200"
              height="260"
              frameborder="0"
              scrolling="no"
            ></iframe>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SideSlide from "~/components/gadget/SideSlide.vue";
import FlexCard from "~/components/gadget/FlexCard.vue";
export default {
  components: { SideSlide, FlexCard },
};
</script>

<style>
.card-article {
  margin-bottom: 20px;
}
.card-article-img {
  margin-bottom: 20px;
}
.card-article-title {
  font-size: 24px;
  margin-bottom: 20px;
  line-height: 35px;
  color: rgba(101, 92, 159, 1);
  font-family: "kanit", sans-serif;
}
.card-article-text {
  font-size: 17px;
  color: #999;
}
.card-article-category {
  font-size: 13px;
  color: rgba(101, 92, 159, 1);
  border-left: 3px solid rgba(101, 92, 159, 1);
  padding-left: 10px;
}
</style>

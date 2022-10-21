<template>
  <div>
    <section class="section" id="blog">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="text-center mb-4">
              <h3>Hình ảnh mới nhất</h3>
              <p class="text-muted mt-2 mb-0">
                Hình ảnh điều trị được chia sẻ mới nhất trên Instagram của chúng
                tôi.
              </p>
            </div>
          </div>
        </div>
        <div class="swiper-container instagramslider">
          <div class="swiper-wrapper pb-5">
            <div class="swiper-slide">
              <div class="card blog-box border-0 mt-4">
                <div class="blog-img position-relative">
                  <img
                    src="~/assets/images/gallery/lcc-01.jpg"
                    alt="LCC Chiropractic 01"
                    class="img-fluid rounded"
                  />
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card blog-box border-0 mt-4">
                <div class="blog-img position-relative">
                  <img
                    src="~/assets/images/blog/blog-02.jpg"
                    alt="Blog"
                    class="img-fluid rounded"
                  />
                  <div class="bg-overlay rounded"></div>
                  <div class="author">
                    <h6 class="fs-16 mb-0">
                      <i
                        class="mdi mdi-account-outline fs-17 align-middle me-1"
                      ></i>
                      Theresa Sinclair
                    </h6>
                    <small
                      ><i
                        class="mdi mdi-clock-outline fs-17 align-middle me-1"
                      ></i>
                      01th July 2021</small
                    >
                  </div>
                </div>
              </div>
            </div>
            <div class="swiper-slide">
              <div class="card blog-box border-0 mt-4">
                <div class="blog-img position-relative">
                  <img
                    src="~/assets/images/blog/blog-03.jpg"
                    alt="Blog"
                    class="img-fluid rounded"
                  />
                  <div class="bg-overlay rounded"></div>
                  <div class="author">
                    <h6 class="fs-16 mb-0">
                      <i
                        class="mdi mdi-account-outline fs-17 align-middle me-1"
                      ></i>
                      Ruben Reed
                    </h6>
                    <small
                      ><i
                        class="mdi mdi-clock-outline fs-17 align-middle me-1"
                      ></i>
                      25th July 2021</small
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="swiper-pagination"></div>
        </div>
      </div>
    </section>
  </div>
</template>

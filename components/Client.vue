<template>
  <div>
    <section
      class="section bg-client bg-light"
      id="client"
    >
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-7">
            <div class="text-center mb-5">
              <h3>Khách hàng của chúng tôi nói gì</h3>
              <p class="text-muted mt-2 mb-0">
                Những chia sẻ của khách hàng sau khi đến điều trị với phòng khám
                của chúng tôi.
              </p>
            </div>
          </div>
          <div class="col-lg-12">
            <div class="swiper-container testimonialslider">
              <div class="swiper-wrapper pb-5">
                <div class="swiper-slide">
                  <div class="testimonial-box text-center card border-0">
                    <div>
                      <div class="testi-img position-relative d-inline-block">
                        <img
                          src="~/assets/images/users/img1.jpg"
                          alt=""
                          class="img-fluid rounded-circle"
                        />
                        <div class="quote-icon">
                          <i class="mdi mdi-format-quote-open"></i>
                        </div>
                      </div>
                      <div class="mt-4">
                        <h6 class="mb-0 fs-17">Minh Tuân</h6>
                      </div>
                    </div>
                    <div class="card-body">
                      <p class="text-muted mb-0">
                        "Tôi đến điều trị rồi, bác sĩ , nhân viên ở đây rất
                        nhiệt tình, quan tâm bệnh nhân , tôi rất hài lòng. "
                      </p>
                    </div>
                    <!--end card-body-->
                  </div>
                  <!--end testimonial-box-->
                </div>
                <div class="swiper-slide">
                  <div class="testimonial-box text-center card border-0">
                    <div>
                      <div class="testi-img position-relative d-inline-block">
                        <img
                          src="~/assets/images/users/img2.jpg"
                          alt=""
                          class="img-fluid rounded-circle"
                        />
                        <div class="quote-icon">
                          <i class="mdi mdi-format-quote-open"></i>
                        </div>
                      </div>
                      <div class="mt-4">
                        <h6 class="mb-0 fs-17">Nguyen Thuy Nga</h6>
                      </div>
                    </div>
                    <div class="card-body">
                      <p class="text-muted mb-0">
                        "Hôm nọ thấy nhiều người khen bên này chữa tốt nên mình
                        cũng đến chữa thoát vị đĩa đệm, thấy hiệu quả thật, điều
                        trị 3 lần khỏi 90% rồi, giờ tôi có thế đi lại, lái ô tô
                        bình thường."
                      </p>
                    </div>
                    <!--end card-body-->
                  </div>
                  <!--end testimonial-box-->
                </div>
                <div class="swiper-slide">
                  <div class="testimonial-box text-center card border-0">
                    <div>
                      <div class="testi-img position-relative d-inline-block">
                        <img
                          src="~/assets/images/users/img3.jpg"
                          alt=""
                          class="img-fluid rounded-circle"
                        />
                        <div class="quote-icon">
                          <i class="mdi mdi-format-quote-open"></i>
                        </div>
                      </div>
                      <div class="mt-4">
                        <h6 class="mb-0 fs-17">Nv Ngọc Mk</h6>
                      </div>
                    </div>
                    <div class="card-body">
                      <p class="text-muted mb-0">
                        "Cô chữa 2 lần thấy khỏi rồi, thì có phải chữa đúng theo
                        liệu trình không hả cháu? vì liệu trình cô 3 lần, thiếu
                        1 lần nữa, thông cảm vì nhà cô ở xa, lần trước cô có để
                        quên cái mũ với phiếu chụp mri, giữ lại giúp cô nhé, cô
                        cảm ơn các cháu đã chưa giúp cô."
                      </p>
                    </div>
                    <!--end card-body-->
                  </div>
                  <!--end testimonial-box-->
                </div>
              </div>
              <div class="swiper-pagination"></div>
            </div>
          </div>
        </div>
        <!--end col-->
      </div>
      <!--end container-->
    </section>
  </div>
</template>
<style scoped>
    .bg-client {
        background-image: url('~assets/images/bg.jpg');
        background-size: cover
    }
</style>

<template>
  <div>
    <section class="bg-cta">
      <div class="bg-overlay"></div>
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="text-center text-white">
              <h3 class="mb-3">LCC Chiropractic</h3>
              <p @click="play" class="play-btn mt-4" data-bs-toggle="modal">
                <i class="mdi mdi-play text-white"></i>
              </p>
            </div>
          </div>
          <!--end col-->
        </div>
        <!--end row-->
      </div>
      <!--end container-->
    </section>
    <ModalPresentationVideo :isPresentationVideo="isPresentationVideo"/>
    <!--end modal-dialog-->
    <div v-if="isPresentationVideo" class="modal-backdrop fade show"></div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isPresentationVideo: false,
    };
  },
  methods: {
    play() {
      this.isPresentationVideo = !this.isPresentationVideo
    }
  }
};
</script>

<style scoped>
.bg-cta {
  background-image: url("assets/images/bg-cta01.jpg");
}
</style>

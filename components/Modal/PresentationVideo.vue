<template>
  <div
    v-if="isPresentationVideo"
    class="modal fade show"
    id="presentationVideo"
    tabindex="-1"
    style="display: block"
  >
    <div class="modal-dialog modal-dialog-centered modal-lg">
      <div class="modal-content bg-transparent border-0">
        <div class="modal-body p-0">
          <div class="text-end">
            <button
              type="button"
              class="btn-close btn-close-white"
              data-bs-dismiss="modal"
              aria-label="Close"
            ></button>
          </div>
          <div class="ratio ratio-16x9">
            <iframe
              width="640"
              height="360"
              src="https://www.youtube.com/embed/qbJ_hcA1Yak"
              title="Welcome To LCC Chiropractic"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>
        <!--end modal-body-->
      </div>
      <!--end modal-content-->
    </div>
  </div>
</template>
<script>
export default {
  props: {
    isPresentationVideo: {
      type: Boolean,
      required: true,
    },
  }
};
</script>


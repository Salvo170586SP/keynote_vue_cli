<template>
  <section id="tikets">
    <div class="container h-100">
      <div class="row h-100 align-items-center">
        <div class="col-12 text-center text-light">
          <h2>TIKETS</h2>
        </div>
        <div class="col-12 col-md-4 d-flex justify-content-center">
          <div class="box-tiket">
            <div class="p-4">
              <h5 class="fw-bold">ONE DAY PASS</h5>
              <span class="text-danger fw-bold">FREE</span>
            </div>
            <div class="text-muted fst-italic p-4">
              <p>One Day Access</p>
              <p>Coffe Breack</p>
              <p>Lunch(International Buffet)</p>
              <p>Document Sheets</p>
              <p>50USD Voucher For Next Event</p>
            </div>
            <a class="bg-danger text-light fw-bold nav-link" href="#">BOOK NOW</a>
          </div>
        </div>
        <div class="col-12 col-md-4 d-flex justify-content-center">
          <div class="box-tiket">
            <div class="p-4">
              <h5 class="fw-bold">FOUR DAY PASSES</h5>
              <span class="text-danger fw-bold">750.00 USD</span>
            </div>
            <div class="text-muted fst-italic p-4">
              <p>Four Day Access</p>
              <p>Coffe Breack</p>
              <p>Lunch(International Buffet)</p>
              <p>Document Sheets</p>
              <p>100USD Voucher For Next Event</p>
            </div>
            <a class="bg-danger text-light fw-bold nav-link" href="#">BOOK NOW</a>
          </div>
        </div>
        <div class="col-12 col-md-4 d-flex justify-content-center">
          <div class="box-tiket">
            <div class="p-4">
              <h5 class="fw-bold">TWO DAY PASS</h5>
              <span class="text-danger fw-bold">580.00 USD</span>
            </div>
            <div class="text-muted fst-italic p-4">
              <p>Two Day Access</p>
              <p>Coffe Breack</p>
              <p>Lunch(International Buffet)</p>
              <p>Document Sheets</p>
              <p>70USD Voucher For Next Event</p>
            </div>
            <a class="bg-danger text-light fw-bold nav-link" href="#">BOOK NOW</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Tikets",
};
</script>

<style scoped lang="scss">
#tikets {
  height: 60vh;
  background-image: url("../assets/image/ticket-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  padding: 50px 0;

  .box-tiket {
    width: 350px;
    background-color: white;
    text-align: center;
  }
}
</style>
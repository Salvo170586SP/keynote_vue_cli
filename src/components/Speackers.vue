<template>
  <section id="speackers">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-11">
          <h2>SPEACKERS</h2>
        </div>
        <div class="col-12 col-md-1 text-end">
          <i class="fa-solid fa-square-caret-left fa-2x text-danger me-2"></i>
          <i class="fa-solid fa-square-caret-right fa-2x text-danger"></i>
        </div>
        <div class="col-12 d-flex justify-content-center flex-wrap mt-3">
          <div class="box-fig">
            <figure>
              <img
                src="../assets/image/speaker-6.jpg"
                class="img-fluid"
                alt=""
              />
            </figure>
            <p class="fw-bold">PATRIK SPENCER</p>
            <span class="text-muted">S&P Analyzer</span>
          </div>
          <div class="box-fig">
            <figure>
              <img
                src="../assets/image/speaker-5.jpg"
                class="img-fluid"
                alt=""
              />
            </figure>
            <p class="fw-bold">JANET JONES</p>
            <span class="text-muted">Network Post's GM</span>
          </div>
          <div class="box-fig">
            <figure>
              <img
                src="../assets/image/speaker-4.jpg"
                class="img-fluid"
                alt=""
              />
            </figure>
            <p class="fw-bold">MICHAEL DOVER</p>
            <span class="text-muted">Starbuks CEO</span>
          </div>
          <div class="box-fig">
            <figure>
              <img
                src="../assets/image/speaker-3.jpg"
                class="img-fluid"
                alt=""
              />
            </figure>
            <p class="fw-bold">ANGELINA HOLY</p>
            <span class="text-muted">Maxii's Manager</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Speackers",
};
</script>

<style scoped lang="scss">
#speackers {
  padding: 80px 0;
  .box-fig {
    width: 200px;
    margin: 0 20px;
    text-align: center;
    figure {
      border-radius: 10px;
      img {
        border-radius: 10px;
      }
    }
    p {
      margin: 0;
    }
    span {
      font-size: 14px;
      font-style: italic;
    }
  }
}
</style>
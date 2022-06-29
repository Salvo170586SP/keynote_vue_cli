<template>
  <section id="subscribe">
    <div class="container h-100">
      <div class="row h-100 align-items-center">
        <div class="col-12 d-flex justify-content-center align-items-center flex-wrap">
          <div class="box-num">
            <span class="fs-1">12153</span> <br />
            <span>DAYS</span>
          </div>

          <div class="box-num">
            <span class="fs-1">17</span> <br />
            <span>HOURS</span>
          </div>
          <div class="box-num">
            <span class="fs-1">28</span> <br />
            <span>MINS</span>
          </div>

          <div class="box-num">
            <span class="fs-1">17</span> <br />
            <span>SECS</span>
          </div>
        </div>
        <div class="col-12 py-3 text-center fw-bold">
          <h5>SUBSCRIBE FOR UPDATES</h5>
        </div>
        <div class="col-12 col-md-4 offset-0 offset-md-3 text-center text-md-end "><input class="p-3" size="35"  type="text" placeholder="Please fill your mail"/></div>
        <div class="col-12 col-md-2 text-center text-md-start my-2"><button class="bg-danger text-light fw-bold btn p-3 ">SUBSCRIBE</button></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Subscribe",
};
</script>

<style scoped lang="scss">
#subscribe {
  /* height: 60vh; */
  padding: 100px 0;
  background-image: url("../assets/image/coutdown-bg1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;

  .box-num {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 150px;
    height: 150px;
    padding: 10px;
    margin: 10px 10px;
    border-radius: 10px;
    background-color: rgba(0, 0, 0, 0.664);
    font-weight: bold;
    text-align: center;
    vertical-align: middle;
    span {
      color: white;
    }
  }
}
</style>
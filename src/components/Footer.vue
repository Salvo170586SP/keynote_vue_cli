<template>
  <footer>
    <section id="top">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-3 py-2 text-center text-md-start">
            <h6 class="list-group-item">ABOUTS US</h6>
            <p class="list-group-item">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Praesentium eveniet voluptate totam sequi amet harum consequatur
            </p>
            <div>
              <i class="fa-brands fa-facebook"></i>
              <i class="fa-brands fa-twitter"></i>
              <i class="fa-brands fa-linkedin"></i>
              <i class="fa-brands fa-google-plus-g"></i>
              <i class="fa-brands fa-pinterest-p"></i>
            </div>
          </div>
          <div class="col-12 col-md-3 py-2 text-center text-md-start">
            <h6>RECENT NEWS</h6>
            <ul class="list-group">
              <li class="list-group-item">
                <a class="text-muted nav-link" href="#"
                  >> SEM PORTA MOLLIS PARTURIENT</a
                >
              </li>
              <li class="list-group-item">
                <a class="text-muted nav-link" href="#"
                  >> NULLAM LOREM MATTIS PURUS</a
                >
              </li>
              <li class="list-group-item">
                <a class="text-muted nav-link" href="#"
                  >> NIBH SEM SIT ULLAMCORPER</a
                >
              </li>
              <li class="list-group-item">
                <a class="text-muted nav-link" href="#"
                  >> MAGNA PARS STUDIORUM</a
                >
              </li>
            </ul>
          </div>
          <div class="col-12 col-md-3 py-2 text-center text-md-start">
            <h6>GET YOUR SEAT!</h6>
            <p>
              Book for your seat befor it's too rate. We provide variety of
              tiket options.
            </p>
            <a href="#" class="btn btn-danger px-3 py-2">CHECH OUT TIKETS!</a>
          </div>
          <div class="col-12 col-md-3 py-2 text-center text-md-start">
            <h6>GALLERY FROM LAST YEAR</h6>
            <div class="box-imgs d-flex justify-content-between flex-wrap">
              <img src="../assets/image/card01-150x150.jpg" width="50" alt="" />
              <img
                src="../assets/image/13349065283_64d09b067c_o-150x150.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/6426608875_186070f8ca_o-150x150.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/speaker-2-150x150.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/speaker-8-150x150.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/6426608875_186070f8ca_o.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/photodune-6745579-modern-creative-man-relaxing-on-workspace- (1).jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/photodune-8522811-speaker-at-business-conference-and-present.jpg"
                width="50"
                alt=""
              />
              <img
                src="../assets/image/photodune-8797753-multiethnic-people-with-startup-business-t (2).jpg"
                width="50"
                alt=""
              />
              <img src="../assets/image/2-item-1.jpg" width="50" alt="" />
              <img src="../assets/image/461365506_960.jpg" width="50" alt="" />
              <img src="../assets/image/ticket-bg.jpg" width="50" alt="" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="bottom">
        <div class="container">
            <div class="row">
                <div class="col-12 col-md-6 text-muted text-center text-md-start">
                    <p>@ Copyright GoodLayers, All right Reserved</p>      
                </div>
                <div class="col-12 col-md-6 text-muted text-center text-md-end">
                    <span class="border-end">About Us</span>      
                    <span class="border-end">Accomodation</span>      
                    <span class="border-end">Call For Paper</span>      
                    <span>Contact Us</span>      
                </div>
            </div>
        </div>
    </section>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
#top {
  background-color: #212121;
  color: white;
  padding: 50px 0;

  .list-group-item {
    background-color: transparent;
    color: white;
    border: 0;
  }

  a {
    font-size: 13px;
    padding: 0;
  }
  .box-imgs {
    width: 250px;
    img {
      margin: 5px;
    }
  }

  i {
    margin: 0 10px;
  }
}
#bottom{
    background-color: #161616;
    color: white;
    padding: 10px 0;
    span{
        padding: 0 10px;
    }
}
</style>
<template>
  <section id="recent-news">
    <div class="container">
      <div class="row">
        <div
          class="
            col-12
            d-flex
            justify-content-between
            align-items-center
            flex-wrap
            py-4
          "
        >
          <h2>RECENT NEWS</h2>
          <a href="#" class="nav-link text-danger">Read All News</a>
        </div>
        <div class="col-12 col-md-4">
          <div class="box-card">
            <figure>
                <img
                  src="../assets/image/photodune-7770665-two-white-coffee-mug-with-diy-decoration-o (2).jpg"
                  class="img-fluid"
                  alt=""
                />
            </figure>
            <p class="text-muted fst-italic">3 Dec 2013 / 0 Comments</p>
            <h5>SEDIA EIUSCMOR TEMPOR</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
              amet quae quam culpa recusandae consequuntur perspiciatis autem
              tempore quos minus. Odit libero hic qui, ipsam cum ducimus
              deleniti nesciunt quo.
            </p>
            <a href="#" class="text-danger fst-italic nav-link px-0">Read More</a>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="box-card">
            <figure>
                <img
                  src="../assets/image/photodune-8797753-multiethnic-people-with-startup-business-t (2).jpg"
                  class="img-fluid"
                  alt=""
                />
            </figure>
            <p class="text-muted fst-italic">3 Dec 2013 / 0 Comments</p>
            <h5>DOCEC LUCTUS IMPERDIECT</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
              amet quae quam culpa recusandae consequuntur perspiciatis autem
              tempore quos minus. Odit libero hic qui, ipsam cum ducimus
              deleniti nesciunt quo.
            </p>
            <a href="#" class="text-danger fst-italic nav-link px-0">Read More</a>
          </div>
        </div>
        <div class="col-12 col-md-4">
          <div class="box-card">
            <figure>
                <img
                  src="../assets/image/photodune-8522811-speaker-at-business-conference-and-present (2).jpg"
                  class="img-fluid"
                  alt=""
                />
            </figure>
            <p class="text-muted fst-italic">3 Dec 2013 / 0 Comments</p>
            <h5>MAGNA PARS STUDIORUM</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam
              amet quae quam culpa recusandae consequuntur perspiciatis autem
              tempore quos minus. Odit libero hic qui, ipsam cum ducimus
              deleniti nesciunt quo.
            </p>
            <a href="#" class="text-danger fst-italic nav-link px-0">Read More</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RecenNews",
};
</script>

<style scoped lang="scss">

#recent-news{
    padding: 50px 0;
}
figure{
    height: 220px;
    object-fit: cover;
    overflow:  hidden;
}
</style>
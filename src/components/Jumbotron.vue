<template>
  <section id="jumbotron">
    <div class="container h-100 ">
        <div class="row h-100 align-items-center">
            <div class="col-12 text-light">
                <div class="d-flex flex-column justify-content-center align-items-center mb-3">
                    <h2 class="fs-1 fw-lighter">CONFERENCE ON</h2> 
                    <h1>SOCIAL NETWORKS</h1>
                </div>
                <div class="d-flex flex-column justify-content-center align-items-center">
                   <p class="py-2 fw-bold"><span class="me-3">23-26 MAY 2019</span>   /  <span class="mx-3">SAN FRANCISCO</span>   /  <span class="ms-3">8 SPEAKERS</span> </p> 
                   <a href="#" class="btn btn-danger p-3 fw-bold">REGISTER ONLINE</a>
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name:"Jumbotron"
}
</script>

<style scoped lang="scss">
#jumbotron{
    height: 60vh;
    background-image: url('../assets/image/slider-1-bg.jpg');
    background-position: center;
    background-size: cover;

    h1{
        font-size: 4rem;
    }
    p{
        border-top: 4px solid white ;
    }
}

</style>
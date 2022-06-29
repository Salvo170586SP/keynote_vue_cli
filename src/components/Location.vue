<template>
  <section id="location">
    <div class="container h-100">
        <div class="row h-100 align-items-center">
            <div class="col-12 d-flex flex-column justify-content-center align-items-center text-light">
                <h2>LOCATION</h2>
                <h2 class="text-center">GD BUILDING, GRAND CONFERENCE ROOM</h2>
                <p><i class="fa-solid fa-location-arrow"></i> 11 GD Building, Rivr Mal, NewYork, USA 8879</p>
                <p class="text-danger">Check For Accomodation Here</p>
                <div class="b w-50 d-flex align-items-center justify-content-center flex-grow">
                    <p><i class="fa-solid fa-phone"></i> +1-255-334-5844 </p> <p><i class="fa-solid fa-envelope ms-3"></i> Contact@TheKeynoteTheme.com</p> 
                </div>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
export default {
    name:"Location"
}
</script>

<style scoped lang="scss">
#location{
    height: 50vh;
    background-image: url('../assets/image/location-bg.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    .b{
        border-top: 1px solid white;
    }
}
</style>
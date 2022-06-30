<template>
  <section id="presentation">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-6">
          <h5 class="fw-bold my-4">PRESENTATION</h5>
          <iframe
            src="https://www.youtube.com/embed/3tmHJHUsiCI"
            title="Apple WWDC 2022 keynote in 24 minutes"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
        <div class="col-12 col-md-6">
          <h5 class="fw-bold my-4">TWITTER FEED</h5>
          <ul class="my-4 list-group">
            <li class="my-3 list-group-item border-0">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum,
                nobis culpa rem doloribus temporibus eos dolorum libero dolorem
                voluptates placeat.
              </p>
              <span class="fst-italic text-muted">3 days ago</span>
            </li>
            <li class="my-3 list-group-item border-0">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum,
                nobis culpa rem doloribus temporibus eos dolorum libero dolorem
                voluptates placeat.
              </p>
              <span class="fst-italic text-muted">9 days ago</span>
            </li>
            <li class="my-3 list-group-item border-0">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum,
                nobis culpa rem doloribus temporibus eos dolorum libero dolorem
                voluptates placeat.
              </p>
              <span class="fst-italic text-muted">11 days ago</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "presentation",
};
</script>

<style scoped lang="scss">
#presentation {
  padding: 50px 0;
    iframe{
        width: 100%;
        height: 300px;
    }
  
}
</style>
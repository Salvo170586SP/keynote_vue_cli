<template>
  <header>
    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <h1>THE KEYNOTE</h1>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse p-3" id="navbarSupportedContent">
            <ul class="navbar-nav justify-content-end flex-grow-1 mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Pages</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link" href="#">Program</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Tikets</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Speackers</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Papers</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Blog</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Shortcodes</a>
              </li>
              <li class="nav-item search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped lang="scss">
header {
  background-color: white;
  position: fixed;
  width: 100%;
  z-index: 10;

  h1 {
    font-size: 2rem;
    font-weight: bold;
  }

  li {
    margin: 0 10px;
  }

    .navbar-light .navbar-nav  .nav-link {
      &:hover {
        color: orange;
        box-shadow: 0 5px 0 0 orange;
      }
      &:focus {
        color: orange;
        box-shadow: 0 5px 0 0 orange;
      }
    }

  .nav-item {
    font-weight: bold;
    font-size: small;
    text-transform: uppercase;
  }

  .search-icon{
    line-height: 2;
  }
}
</style>
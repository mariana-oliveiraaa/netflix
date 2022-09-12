<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="nome text-center ">
    <h1>ULTRAFLIX</h1>
  </div>

  <nav class="navbar navbar-expand-lg navbar-light cor1">
    <a class="navbar-brand" href="#">ULTRAFLIX</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#"> FILMES <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"> SÉRIES</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"> BOMBANDO</a>
        </li>
      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Procurar</button>
      </form>
    </div>
  </nav>


  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="@/assets/images/herry.png" alt="First slide">
      </div>FAVORITOS
      <div class="carousel-item">
        <img class="d-block w-100" src="@/assets/images/VELOZES.jpeg" alt="Second slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="@/assets/images/homemaranha.jpg" alt="Third slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>

  <div class="container cor1">
    <h2>Favoritos</h2>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-md-3">
        <img src="@/assets/images/img3.jpg" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="@/assets/images/img6.png" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="@/assets/images/img7.jpg" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="@/assets/images/img4.jpg" class="img-fluid" alt="Responsive image">
      </div>
    </div>
  </div>

  <div class="container cor1">
    <h2>Assistir mais tarde</h2>
  </div>

  <div class="container">
    <div class="row">
      <div class="col-md-3">
        <img src="img11.jpg" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="img30.jpg" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="img50.jpg" class="img-fluid" alt="Responsive image">
      </div>
      <div class="col-md-3">
        <img src="img40.jpg" class="img-fluid" alt="Responsive image">
      </div>
    </div>
  </div>





















</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>


<template>
  <div id="app">
    <header>
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand logo" href="#">bohèmeGal</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Log In <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Categories
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Women</a>
          <a class="dropdown-item" href="#">Men</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Sales</a>
        </div>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-danger my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
     </nav>
    </header>
    <router-view/>
    <footer>
      <p>© Copyright 2018 - Bohème Gal</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  color: #2c3e50;
}

footer {
  bottom: 0;
  display: block;
  width: 100vw;
  height: 10vh;
  text-align: center;
  font-weight: bolder;
}

.logo{
    font-size: 2em;
    font-family: 'Lobster', cursive;
}
.bg-light {
    background-color: #FAD7A0!important;
}

.btng {
  width: 300px;
}
</style>

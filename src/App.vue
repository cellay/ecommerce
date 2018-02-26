
<template>
  <div id="app">
    <header>
     <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo03" aria-controls="navbarTogglerDemo03" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <a class="navbar-brand logo" href="#">bohèmeGal</a>
              
                <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
                  <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Categoría
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            
                        </div>
                        </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">Inicia sesión</a>
                    </li>
                    <form class="form-inline">
                            <input class="form-control mr-sm-2" type="search" placeholder="busca algo interesante" aria-label="Search">
                            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                          </form>
                  </ul>
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
  text-align: center;
  color: #2c3e50;
}

footer {
  width: 100vw;
  height: 10vh;
  position: absolute;
  bottom: 0;
}

.logo{
    font-size: 6vh;
    font-family: 'Lobster', cursive;
}
.bg-light {
    background-color: #FAD7A0!important;
}
.btn-outline-success {
    color: black;
    background-color: transparent;
    background-image: none;
    border-color: black;
}
.btn-outline-success:hover{
    background-color: white;
    color: black
}
</style>

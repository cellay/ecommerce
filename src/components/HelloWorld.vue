<template>
  <div class="hello">
    <div class="container">
      <div class="row d-flex justify-content-around align-items-center">
        <div class="col-8">
          <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="https://drscdn.500px.org/photo/97003111/q%3D80_m%3D1500/v2?webp=true&sig=4568163cc07267f2c800f6df7c69e67add085eca65ca8ef1dc9078b5bf601754" alt="First slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drscdn.500px.org/photo/238774923/q%3D80_m%3D1500_k%3D1/v2?webp=true&sig=f2780130fbbd74bcd99f5f516821743a4f9b5f27d7bbb18110879d99a3d9ec75" alt="Second slide">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="https://drscdn.500px.org/photo/236992933/q%3D80_h%3D300/v2?webp=true&sig=97bc387f8b4660bf62a068487ed22d39a195b3068bc120fc7089de13503eeadd" alt="Third slide">
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
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row d-flex justify-content-around align-items-center btnbox">
        <router-link to="/women"><button class="btn btn-outline-danger">Women</button></router-link>
        <router-link to="/men"><button class="btn btn-outline-danger">Men</button></router-link>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.row {
  margin-top: 20px;
}

.btnbox {
  height: 10vh;
}
</style>

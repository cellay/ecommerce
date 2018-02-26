
<template>
  <div id="app">
    <header>
      <nav class="navbar navbar-light bg-light">
        <span class="navbar-brand mb-0 h1">Bohème</span>
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
</style>

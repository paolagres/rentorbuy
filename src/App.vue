<template>
  <div class="app">
    <div class="ui secondary menu">
      <div class="left menu">
        <img alt="Pretto logo" src="@/assets/logo-pretto.png" style="text-align: left"/>
      </div>
      <a class="item">
        <router-link to="/">Calculette</router-link>
      </a>
      <a class="item">
        <router-link to="/about">Données</router-link>
      </a>
      <a class="item">
        <router-link to="/old">Avec estimations</router-link>
      </a>
    </div>
    <div class="ui divider"></div>
    <router-view />
  </div>
</template>

<style>

.app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.ui.secondary.menu {
  margin: 10px;
  text-align: center;
  font-size: 1.5rem;
}

.item > a {
  font-weight: bold;
  color: #2c3e50;
}

.item > .router-link-exact-active {
  color: #42b983;
}

img {
  height: 40px;
  text-align: left;
  margin: 20px;
}

.left.menu {
  font-size: 3rem;
}

</style>

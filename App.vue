<template>
  <div id="app">
    <div id="nav">
      <router-link class="nav" to="/">Home</router-link>
      <router-link class="nav" to="/about">About</router-link>
      <router-link class="nav" to="/Three">Three</router-link>
      <router-link class="nav" to="/four">Four</router-link>
      </div>
    <router-view/>
  </div>
</template>

<style>
* {
  margin: 0px;
  padding: 0px;
} .nav {
  padding-left: 4vw;
  padding-right: 4vw;
  text-decoration: none;
  color: white;
  padding-top: 3vw;
} #nav {
  background: orange;
  height: 10vw;
  font-size: 5vw;
  text-align: center;
  padding-top: 2vw;
}

</style>

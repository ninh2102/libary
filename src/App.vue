import router from './router';

<template>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
h1{
  font-family:  'Times New Roman', Times, serif;
  font-size: 30px;
}
h2{
  font-family: 'Times New Roman', Times, serif;
}
nav {
  text-align: center;
  padding: 30px;
  border-bottom: 1px solid black;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
li {
  list-style: none;
  text-align:left;
}
</style>

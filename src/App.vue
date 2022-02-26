<template>
  <nav>
    <h3>CariinKerja</h3>
    <router-link to="/">Home</router-link>
    <router-link to="/postjob">Post Job</router-link>
    <router-link to="/about">About</router-link>
    <button>Login</button>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
h3 {
  text-align: left;
  float: left;
  font-weight: bold;
}

button {
  float: right;
  text-decoration: none;
  background: #4324ce;
  color: white;
  border: none;
  padding: 9px;
  border-radius: 10px;
}

button:hover {
  background: blueviolet;
  color: wheat;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  margin: 10px;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: #4324ce;
}
</style>

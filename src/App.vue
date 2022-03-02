<template>
  <nav>
    <h3>CariinKerja</h3>
    <router-link to="/">Home</router-link>
    <router-link to="/postjob">Post Job</router-link>
    <router-link to="/about">About</router-link>
    <router-link class="btn-login" to="/login">Login</router-link>
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
nav h3 {
  text-align: left;
  float: left;
  font-weight: 800;
}

nav button {
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
  color: white;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
  margin: 10px;
  text-decoration: none;
  padding: 10px;
}

nav a.router-link-exact-active {
  color: #4324ce;
}

nav a:hover {
  background: rgb(196, 183, 226);
  border-radius: 10px;

}

/* btn-login */

.btn-login {
  float: right;
  margin-top:0;
  padding-top: 0;
  background: #4324ce;
  padding-bottom: 0;
  padding: 5px;
  color: white;
  border-radius: 10px;
}
.btn-login:hover {
  background: #8c79e0;
}
</style>

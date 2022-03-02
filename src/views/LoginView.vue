<template>
  <div class="login">
      <div class="container1">
      <h1>Best Talent</h1>
      <h2>for</h2>
      <h1>Best Company</h1>
      </div>
      <img class="icon-banner" src="../assets/Saly.png" alt="">
      <div class="form">    
      <input type="text" v-model="email" placeholder="Enter Email" />
      <input type="password" v-model="password" placeholder="Enter password"/>
      <button v-on:click="login">Login</button>
      </div>   
  </div>
</template>

<script>
import axios from 'axios'
export default {

    name: "LoginView",
    data()
    {
        return {
            email:'',
            password:''
        }
    },
    methods: {
        async login()
        {
            let result = await axios.get(
                `http://54.255.4.75:9091/api/v1/auth/recruiter/login?recruiterEmail=${this.email}&recruiterPassword=${this.password}`
            )
            console.warn(result)
        }
    }
};
</script>

<style scoped>
.login {
    background: red;
    display: flex;
    flex-direction: row;
}
.container1 {
    padding: 70px;
    font-size: 20px;
    margin-left: 20px;
}
.icon-banner {
    width: 150px;
    height: 150px;
}
.form {
    display: flex;
    flex-direction: column;
    margin: 20px;
    margin-left: 400px;
    padding: 2px;
}
input {
    padding: 5px;
    border: none;
    margin: 2px;
}
input [type="text"] {
    border: none;
    border-bottom: 1px solid #ddd;
}


</style>


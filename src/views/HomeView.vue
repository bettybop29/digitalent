<template>
<div class="bgwhite">
  <div class="home">
    <h1>Find The Best Fit <br> For Your Team</h1>
    <img alt="Vue logo" src="../assets/banner.png">      
  </div>
  </div>
  <div class="bg-gradient">
  <h2>How can we help your business</h2>
 
  
  <div class="main-card">
    <div class="card">
      <img src="../assets/icon/CREDIT.svg" alt="">
      <div class="card-title">Credits</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea cumque rem harum molestias 
        fugit labore vel mollitia, alias esse reiciendis. Voluptatibus ut dolor assumenda sequi eos, 
        a inventore libero facere?</P>
    </div>
    <div class="card">
      <img src="../assets/icon/POSTJOB.svg" alt="">
      <div class="card-title">Post Jobs</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea cumque rem harum molestias 
        fugit labore vel mollitia, alias esse reiciendis. Voluptatibus ut dolor assumenda sequi eos, 
        a inventore libero facere?</P>
    </div>
    <div class="card">
      <img src="../assets/icon/INTERVIEW.svg" alt="">
      <div class="card-title">interview Schedule</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea cumque rem harum molestias 
        fugit labore vel mollitia, alias esse reiciendis. Voluptatibus ut dolor assumenda sequi eos, 
        a inventore libero facere?</P>
    </div>
  </div>
  
  
  <h2>Our Satisfied Partners</h2>
  <div class="sponsor">
    <img src="../assets/sponsor/BNI.png" alt="">
    <img src="../assets/sponsor/KAO.png" alt="">
    <img src="../assets/sponsor/TIX.png" alt="">
    <img src="../assets/sponsor/DENTSU.png" alt="">
    <img src="../assets/sponsor/SHARP.png" alt="">
    <img src="../assets/sponsor/ANA.png" alt="">
  </div>

<!-- footer -->
<footer>
  <div class="container">
  <p class="logo-footer">Cariin kerja</p>
    <h4>Jl. Sudirman Jakarta Pusat</h4>
  </div>
      <div class="content">
        <ul>Company</ul>
        <li>About US</li>
        <li>Blog</li>
        <li>Carrer</li>
      </div>
      <div class="content">
        <ul>Features</ul>
        <li>Review</li>
        <li>Community</li>
        <li>Social Media</li>
      </div>
      <div class="content">
        <ul>Help</ul>
        <br>
        <li>Support@gmail.com</li>
        <li>+628653240093</li>
      </div>
 
 
 
</footer>
<hr>
<h5>2022 Copyright Connect. All Rights reserved</h5>
</div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',
  
}
</script>
<style scoped>
.home {
  padding: 0;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 0;
  margin-top: 50px;
}
.home img {
  margin-right: 30px;
}
h1 {
  text-align: left;
  margin-left: 60px;
  font-size: 50px;
}
h2 {
  padding-top: 90px;
  font-size: 35px;
  padding-bottom: 80px;
  color: white;
  
}
.card {
  background-color: #0A0F16;
  width: 300px;
  height: 300px;
  border-radius: 20px;
  color: white;
  padding: 20px;
  align-items: center;
  margin: 10px;
  text-align: left;
  box-shadow: 0 5px 10px rgb(0 0 0 / 0.2);
}
.card-title {
  text-align: left;
  margin: 0px;
  font-weight: bolder;
  font-size: 25px;
  padding-top: 20px;
  padding-bottom: 20px;
}
.card img {
  width: 50px;
}
.main-card {
  display: flex;
  flex-direction: row;
  margin: 20px;
  justify-content: center;
}
.sponsor img{
  margin: 20px;
}

footer {
  text-align: left;
  text-decoration: none;
  margin: 0;
  padding: 20px;
  color: white;
  background-color: #101419; 
  padding-top: 90px; 
}
footer p {
  font-size: 30px;
}
footer ul {
  font-size: 20px;
  font-weight: 700;
  padding-bottom: 10px;
}
footer li {
  padding: 4px;
}
.content {
  display: inline-block;
  list-style-type: none;
  margin-left: 350px;
}

h5 {
  background-color: #101419;
  padding: 30px;
  color: white;
}



.logo-footer {
  padding-bottom: 20px;
}


/* colorbg-gradient */

.bg-black {
  background: #101419;
}
.bg-black-blue {
  background-image: linear-gradient(#2E2E78,#101419 );
}
.bg-blue-white {
  background-image: linear-gradient(white,#2e2e78 );
}
.bg-gradient {
  background-image: linear-gradient(#2E2E78, #101419 50%);
}
.bgwhite {
  background-image: linear-gradient(#ffffff, #2E2E78);
}

</style>

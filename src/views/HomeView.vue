<template>
  <div class="home">
    <h1>Find The Best Fit <br> For Your Team</h1>
    <img alt="Vue logo" src="../assets/banner.png">      
  </div>
  <h2>How can we help your business</h2>
  <div class="main-card">
    <div class="card">
      <img src="../assets/icon/CREDIT.svg" alt="">
      <div class="card-title">Credits</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
    </div>
    <div class="card">
      <img src="../assets/icon/POSTJOB.svg" alt="">
      <div class="card-title">Post Jobs</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
    </div>
    <div class="card">
      <img src="../assets/icon/INTERVIEW.svg" alt="">
      <div class="card-title">interview Schedule</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
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
  margin: 20px;
  background-color: red;
}
h1 {
  text-align: left;
  margin-left: 40px;
  font-size: 50px;
}
h2 {
  padding-top: 50px;
  font-size: 35px;
  
}
.card {
  background-color: #101419;
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

</style>

<template>
  <div class="home">
    <h1>Find The Best Fit <br> For Your Team</h1>
    <img alt="Vue logo" src="../assets/logo.png">      
  </div>
  <h2>How can we help your business</h2>
  <div class="main-card">
    <div class="card">
      <div class="card-title">Credits</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
    </div>
    <div class="card">
      <div class="card-title">Credits</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
    </div>
    <div class="card">
      <div class="card-title">Credits</div>
      <P>Lorem, ipsum dolor sit amet consectetur adipisicing elit. 
        Aliquam tenetur accusantium earum ab nisi aut,
        Id, veniam provident autem est quam enim.</P>
    </div>
  </div>
  <h2>Our Satisfied Partners</h2>
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
}
h1 {
  text-align: left;
  margin-left: 30px;
}
h2 {
  padding-top: 30px;
}
.card {
  background-color: aqua;
  width: 200px;
  border-radius: 20px;
  color: white;
  padding: 20px;
  align-items: center;
  margin: 10px;
  text-align: left;
  
}
.card-title {
  text-align: left;
  margin: 0px;
  font-weight: bolder;
}
.main-card {
  display: flex;
  flex-direction: row;
  margin: 20px;
  justify-content: center;
}

</style>

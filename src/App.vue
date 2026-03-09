<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <div class="page">

    <div class="card">

      <img src="./assets/profile.jpeg" alt="Profile Photo" class="profile">

      <h1>Excel Tri Dermawan</h1>

      <p class="nim">NIM 12450111812</p>

      <h2>Informatics Engineering Student</h2>

      <p class="desc">
        An Informatics Engineering student who explores creativity across
        digital and artistic fields. My work spans game design, music
        production, and content creation, where technology becomes a medium
        to express emotion and storytelling.
      </p>

    </div>

  </div>
</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

body{
  margin:0;
  font-family:'Poppins', sans-serif;
}

.page{
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;

  background:linear-gradient(135deg,#0f172a,#1e293b,#020617);
}

.card{

  text-align:center;

  background:rgba(255,255,255,0.05);
  backdrop-filter:blur(10px);

  padding:60px 40px;

  border-radius:20px;

  width:420px;

  box-shadow:0 20px 50px rgba(0,0,0,0.5);

  color:white;
}

.profile{
  width:220px;
  height:220px;

  border-radius:50%;

  object-fit:cover;

  border:5px solid #42b883;

  margin-bottom:20px;

  box-shadow:0 10px 25px rgba(0,0,0,0.6);
}

h1{
  font-size:32px;
  margin-bottom:5px;
}

.nim{
  color:#94a3b8;
  margin-bottom:10px;
}

h2{
  color:#42b883;
  font-weight:500;
  font-size:18px;
  margin-bottom:20px;
}

.desc{
  font-size:15px;
  line-height:1.7;
  color:#cbd5f5;
}

</style>
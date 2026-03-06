<script setup>
// import HeroSection from '../components/HeroSection.vue'
import CNN_Project from '@/components/CNN_Project.vue';

</script>


<template>
  <section class="hero">
    <div class="left">
      <div class="profile">
        <img src="/public/Profile.jpg" alt="Profile Picture" class="ProfilePicture">
      </div>
      <div class="information">
        <h1> Hi my name is Tanakron Punjasuntorn</h1>
      </div>
      <div class="aboutme">
        <p>Age : 21</p>
        <p>Email : tanakron1748@gmail.com</p>
        <p>Phone : 065-746-9338</p>
        <p>University : Bangkok University</p>
        <p>Major : Engineering (Computer and Robotics Engineering)</p>
      </div>
    </div>

    <div class="right">

      <div class="row">

        <router-link to = "/ForDev">
          <div class="CNN" @click="ForDev">
            <CNN_Project />
          </div>
        </router-link>
  
      
 
      </div>

      


    </div>
  </section>
</template>

<style>

:root{
  --font-size: 13px;
}

.hero {
  display: flex;
  min-height: 100vh;
}

.left {
  width: 30%;
  /* background-color: red; */
}

.right {
  width: 70%;
  display: flex;
  flex-direction: column;
  gap: 50px;
  /* background-color: blue; */
}

.profile {
  background-color: green;
  margin-left: 10%;
  margin-top: 40%;

  width: 400px;
  height: 500px;
}

.ProfilePicture {
   width: 100%;
   height: 100%;
}

.information {
  margin-top: 25px;
  margin-left: 10%;
  font-size: 10px;
}

.aboutme p{
  margin-left: 10%;
  font-size: var(--font-size);
}

.row {
  display: flex;
  flex-direction: row;
  gap: 50px;
}

.CNN {
  max-height: 500px;
  margin-top: 60px;
  /* margin-bottom: 10px; */
  /* padding-left: 60px; */
}
</style>

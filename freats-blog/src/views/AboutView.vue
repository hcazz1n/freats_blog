<script setup>
import TheNavigation from '../components/TheNavigation.vue'
</script>

<template>
  <div class="home-container">
    <TheNavigation />
    <div class="main-container columns">
      <div class="container left-about column">
        <div class="about-container">
          <h1 class="about-text about-title">Fred He - Me!</h1>
          <h1 class="about-text about-content">
            H! I’m Fred He, and I’m currently a grade 12 student. When I’m not stressing over school
            or studying for tests, you can find me in the kitchen, stuffing my face with whatever I
            can find. Throughout the entirety of my life, food has been an utmost importance to me,
            as it’s not only delicious and mouth-watering, but acts as a way for me to connect with
            my culture. This, in combination with an interest in computer science led me to create
            this blog. I love eating, and hope that I’ll be able to document lots of my journey to
            share with everyone through FREATS.
          </h1>
        </div>
      </div>
      <div class="container right-about column">
        <img src="../../public/about.jpg" class="about-image" />
      </div>
    </div>
  </div>
</template>

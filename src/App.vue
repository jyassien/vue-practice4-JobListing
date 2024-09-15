<template>
<Navbar/>
<RouterView />


<!-- <Hero title="Test Title" subtitle="Test Subtitle"/> -->
<!-- <Hero />
<HomeCards />
<JobListings :limit="4"  :showButton="true"/> -->
</template>


<script setup>
import Navbar from './components/Navbar.vue';
import { RouterView } from 'vue-router';
// import Hero from './components/Hero.vue';
// import HomeCards from './components/HomeCards.vue';
// import JobListings from './components/JobListings.vue';
</script>
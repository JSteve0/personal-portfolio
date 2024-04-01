<template>
  <main>
    <side-bar />

    <div class="main-content">
      <navbar/>

      <about-page/>

      <resume-page/>

      <portfolio-page/>

<!--      <blog-page/>-->

      <contact-page/>

    </div>

  </main>
</template>
<script setup>
import SideBar from "@/components/SideBar.vue";
import Navbar from "@/components//Navbar.vue";
import AboutPage from "@/components//AboutPage.vue";
import ResumePage from "@/components//ResumePage.vue";
import PortfolioPage from "@/components//PortfolioPage.vue";
import ContactPage from "@/components//ContactPage.vue";
</script>
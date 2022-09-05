<template>
  <div class="homepage-yellow">
    <Navbar />
    <HomeContent />
    <FooterHome />
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import HomeContent from "./HomeContent.vue";
import FooterHome from "./FooterHome.vue";
export default {
    name: "Homepage",
    components: { Navbar, HomeContent, FooterHome }
}
</script>

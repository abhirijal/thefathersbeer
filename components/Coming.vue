<template>
  <div class="position-fixed top-50 start-50 translate-middle text-center">
    <img class="header-logo mb-5 mx-auto" src="/img/logo.png" alt="">
    <div class="p-5 rounded-3">
      <h2 class="font-daniel">coming soon</h2>
    </div>
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import HomeContent from "./HomeContent.vue";
import FooterHome from "./FooterHome.vue";
export default {
    name: "Coming",
    components: { Navbar, HomeContent, FooterHome }
}
</script>

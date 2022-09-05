<template>
  <div class="position-fixed top-50 start-50 translate-middle text-center">
    <img class="header-logo mb-5 mx-auto" src="/img/logo.png" alt="">
    <div class="homepage-yellow p-5 rounded-3">
      <h2 class="font-daniel">Are you 18 or over?</h2>
      <div class="d-flex justify-content-center mt-4" style="column-gap: 30px;">
        <span class="text-white px-3 py-2 border rounded-1" style="background-color: #000;">
          <span class="font-daniel">Yes, I am.</span>
        </span>
        <span class="bg-light text-dark px-3 py-2 border rounded-1 border-dark" style="background-color: #000;">
          <span class="font-daniel">No, go back.</span>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import HomeContent from "./HomeContent.vue";
import FooterHome from "./FooterHome.vue";
export default {
    name: "Age",
    components: { Navbar, HomeContent, FooterHome }
}
</script>

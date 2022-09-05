<template>
  <div>
    <Navbar />
    <ContactContent />
    <FooterHome />
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import FooterHome from "./FooterHome.vue";
import ContactContent from "./ContactContent.vue";
export default {
    name: "WhatTheFog",
    components: { Navbar, FooterHome, ContactContent }
}
</script>

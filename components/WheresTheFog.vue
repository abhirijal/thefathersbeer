<template>
  <div>
    <Navbar />
    <WheresTheFogContent />
    <FooterHome />
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import FooterHome from "./FooterHome.vue";
import WhatTheFogContent from "./WhatTheFogContent.vue";
export default {
    name: "WheresTheFog",
    components: { Navbar, FooterHome, WhatTheFogContent }
}
</script>

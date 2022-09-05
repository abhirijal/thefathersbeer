<template>
  <div>
    <Navbar />
    <WhatTheFogContent />
    <FooterHome />
  </div>
</template>

<script>
import Navbar from "./Navbar.vue";
import FooterHome from "./FooterHome.vue";
import WhatTheFogContent from "./WhatTheFogContent.vue";
export default {
    name: "WhatTheFog",
    components: { Navbar, FooterHome, WhatTheFogContent }
}
</script>

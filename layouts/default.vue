<template>
  <Nuxt />
</template>
  
<script>
  export default {
    watch: {
      $route() {
        document.body.style = "";
      },
    },
  }
</script>
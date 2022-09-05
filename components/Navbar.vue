<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="d-flex justify-content-center py-3 nav-gap">
      <div class="w-25">
      <div class="d-flex justify-content-end nav-gap">
      <div class="custom-nav-items align-items-center">
        <NuxtLink class="menu-item-border pb-2" to="/">
            <span class="font-cj navitems">Home</span>
        </NuxtLink>
      </div>
      <div class="custom-nav-items align-items-center">
        <NuxtLink class="menu-item-border pb-2" to="/what-the-fog">
        <span class="font-cj navitems">WHAT THE FOG?</span>
        </NuxtLink>
      </div>
      </div>
      </div>
      <div class="border-bottom border-5 border-blue">
        <NuxtLink to="/">
          <img class="header-logo mb-2" src="/img/logo.png" alt="">
       </NuxtLink>
      </div>
      <div class="w-25">
      <div class="d-flex justify-content-start nav-gap">
        <div class="custom-nav-items align-items-center">
        <NuxtLink class="menu-item-border pb-2" to="/wheres-the-fog">
        <span class="font-cj navitems">WHERE’S THE FOG?</span>
        </NuxtLink>
      </div>
      <div class="custom-nav-items align-items-center">
        <NuxtLink class="menu-item-border pb-2" to="/contact">
        <span class="font-cj navitems">CONTACT</span>
        </NuxtLink>
      </div>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

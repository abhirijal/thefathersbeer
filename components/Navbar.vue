<!-- Please remove this file from your project -->
<template>
  <div>
    <!-- Desktop Navbar -->
    <div class="d-none d-md-block">
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
        <NuxtLink class="menu-item-border pb-2" to="#">
        <span class="font-cj navitems">SHOP</span>
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
    <!-- Desktop Navbar END -->

    <!-- Mobile Navbar -->
    <div class="d-md-none">
      <div class="mobile-header container-xl mb-4">
        <div class="px-3 py-3">
          <div class="d-flex flex-row justify-content-between">
          <div class="border-bottom border-5 border-blue d-flex align-self-center">
            <NuxtLink to="/">
              <img class="header-logo-mobile mb-2" src="/img/logo.png" alt="">
          </NuxtLink>
          </div>
          <div class="d-flex align-self-center">
            <span type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample" aria-controls="offcanvasExample">
            <svg height="45px" width="45px" style="filter: invert(9%) sepia(77%) saturate(6590%) hue-rotate(210deg) brightness(91%) contrast(105%);" clip-rule="evenodd" fill-rule="evenodd" stroke-linejoin="round" stroke-miterlimit="2" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="m11 16.745c0-.414.336-.75.75-.75h9.5c.414 0 .75.336.75.75s-.336.75-.75.75h-9.5c-.414 0-.75-.336-.75-.75zm-9-5c0-.414.336-.75.75-.75h18.5c.414 0 .75.336.75.75s-.336.75-.75.75h-18.5c-.414 0-.75-.336-.75-.75zm4-5c0-.414.336-.75.75-.75h14.5c.414 0 .75.336.75.75s-.336.75-.75.75h-14.5c-.414 0-.75-.336-.75-.75z" fill-rule="nonzero"/></svg>
            </span>
          </div>
        </div>
        </div>
      </div>
    </div>
    <!-- Mobile Navbar END -->

    <!-- OFFCANVAS -->

  <div class="offcanvas offcanvas-end homepage-yellow" tabindex="-1" ref="menuOffcanvas" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel">
  <div class="offcanvas-header">
    <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body custom-nav-items">
    <hr class="mb-1">
    <div>
      <NuxtLink class="menu-item-border pb-2" to="/"
      event=""
      @click.native="closeOffcanvas('/')">
            <span class="font-cj navitems">Home</span>
        </NuxtLink>
    </div>
    <hr class="mt-3 mb-1">
    <div>
      <NuxtLink class="menu-item-border pb-2" to="/what-the-fog"
      event=""
      @click.native="closeOffcanvas('/what-the-fog')">
        <span class="font-cj navitems">WHAT THE FOG?</span>
        </NuxtLink>
    </div>

    <hr class="mt-3 mb-1">
        <NuxtLink class="menu-item-border pb-2" to="/wheres-the-fog">
        <span class="font-cj navitems">WHERE’S THE FOG?</span>
        </NuxtLink>
    <hr class="mt-3 mb-1">
        <NuxtLink class="menu-item-border pb-2" to="/contact">
        <span class="font-cj navitems">CONTACT</span>
        </NuxtLink>
    <hr class="mt-3">
  </div>
</div>

    <!-- OFFCANVA END -->
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  methods: {
    closeOffcanvas(path) {
      var bsOffcanvas = new bootstrap.Offcanvas(this.$refs.menuOffcanvas);
      bsOffcanvas.hide();

      this.$router.push({ path, query });
    }
  }
}
</script>

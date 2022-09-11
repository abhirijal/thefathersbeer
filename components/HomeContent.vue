<!-- Please remove this file from your project -->
<template>
  <div>
    <div>
      <div class="pb-4 mt-4">
        <div class="text-center">
        <img class="homepagecan" src="/img/homepage-can.png" />
      </div>
      <div class="text-center mt-4">
        <span class="font-daniel fs-3 text">nurtured in hunter,s hill</span>
      </div>
      <div class="text-center py-4">
        <img class="imdifferent" src="/img/imdifferent.png" />
      </div>
      <div class="text-center mt-3">
        <NuxtLink to="/what-the-fog">
        <span class="text-white px-3 py-2 rounded-1 me-2" style="background-color: #000;">
          <span class="font-cj fs-2">Decoding the artwork</span>
        </span>
        </NuxtLink>

        <NuxtLink to="/what-the-fog">
        <span class="text-white px-3 py-2 rounded-1 me-2" style="background-color: #000;">
          <span class="font-cj fs-2">The balcony project</span>
        </span>
        </NuxtLink>
        
        <NuxtLink to="/wheres-the-fog">
        <span class="bg-light text-dark px-3 py-2 rounded-1 border-dark ms-2" style="background-color: #000;">
          <span class="font-cj fs-2">Shop</span>
        </span>
        </NuxtLink>        
        <NuxtLink to="/wheres-the-fog">
        <span class="bg-light text-dark px-3 py-2 rounded-1 border-dark ms-2" style="background-color: #000;">
          <span class="font-cj fs-2">Unleash the Fog</span>
        </span>
        </NuxtLink>
      </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeContent'
}
</script>

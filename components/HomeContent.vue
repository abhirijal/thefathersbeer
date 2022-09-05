<!-- Please remove this file from your project -->
<template>
  <div>
    <div>
      <div class="pb-4">
        <div class="text-center">
        <img class="homepagecan" src="/img/homepage-can.png" />
      </div>
      <div class="text-center py-4">
        <img class="imdifferent" src="/img/imdifferent.png" />
      </div>
      <div class="text-center">
        <span class="font-daniel fs-4 text">unleash the fog</span>
      </div>
      <div class="text-center mt-3">
        <NuxtLink to="/what-the-fog">
        <span class="text-white px-3 py-2 border rounded-1 me-2" style="background-color: #000;">
          <span class="font-cj fs-4">What the fog?</span>
        </span>
        </NuxtLink>
        
        <NuxtLink to="/wheres-the-fog">
        <span class="bg-light text-dark px-3 py-2 border rounded-1 border-dark ms-2" style="background-color: #000;">
          <span class="font-cj fs-4">Where's the fog?</span>
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

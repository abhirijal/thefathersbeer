<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="container-xl py-5 homepage-yellow">
      <div class="mx-auto" style="width: 90vw; max-width: 400px">
        <h3 class="font-daniel text-center mb-4">Contact Us</h3>
        <form class="font-tg">
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Name</label>
    <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
  </div>
  <div class="mb-3">
  <label for="exampleFormControlTextarea1" class="form-label">Message</label>
  <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
</div>
        <span class="text-white px-3 py-2 border rounded-1 me-2" style="background-color: #000;">
          <span class="font-daniel fs-6">Send Message</span>
        </span>
</form>
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactContent'
}
</script>

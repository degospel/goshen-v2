<template>
  <div class="partner-hero">
    <div class="partner-body section-content container">
      <div class="partner-content text-center">
        <div class="section-header-big mb-1">
          <p>Your best bet to <br> Make More <span class="span-gradient">Impact!</span></p>
        </div>

        <div class="mb-2">
          <p>
            Whether you’re a community or a content creator in Web3, let’s collaborate and shape the future.
          </p>
        </div>

        <div class="mb-3">
          <div class="partner-hero-img">
            <img src="/img/image_fx_ (93).png" class="img-fluid" alt="">
          </div>
        </div>

        <div class="d-flex justify-content-center mt-3">
          <button class="btn join-btn">Become a Partner</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.partner-hero {
  position: relative !important;
  height: 120vh;
  width: 100%;
  background: url('/img/Ellipse 2.png') no-repeat center;
  background-size: contain;
}

.partner-body {
  position: absolute !important;
  top: 50% !important;
  left: 50% !important;
  transform: translate(-50%, -50%) !important;
  width: 100%;
  /* height: 100%; */
}

.span-gradient {
  background: linear-gradient(91.25deg, #026F7E -1%, #0DFD7E 164.59%) !important;
  background-clip: text !important;
  -webkit-text-fill-color: transparent;
}

.partner-hero-img img{
  border: 1px solid transparent;
  border-radius: 10px;
}

.join-btn {
  background: #026F7E !important;
  border: 1px solid #026F7E;
  border-radius: 12px;
  padding: 10px 20px !important;
  text-transform: capitalize;
  color: #fff;
  text-align: center;
}
</style>

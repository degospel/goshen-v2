<template>
  <div class="community-hero">
    <div class="section-content community-body text-center container">
      <div class="community-content mb-5">
        <div class="section-header-big py-4">
          <p>Join a Vibrant network of <span class="span-gradient">Web3 enthusiasts and professionals</span></p>
        </div>

        <div>
          <span>
            We believe learning and growth happens best within a supportive community. That’s why we have created a
            network where you can meet, connect and collaborate with other non-technical talents in Web3. 
          </span>
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
.community-hero {
  position: relative !important;
  height: 120vh;
  width: 100%;
  background: url('/img/Ellipse 2.png') no-repeat center;
  background-size: contain;
}

.community-body {
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
</style>

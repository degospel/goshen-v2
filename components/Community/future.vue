<template>
  <div class="join-future-section py-5">

    <div class="join-bg-img">
      <img src="/img/Ellipse 16.png" alt="">
    </div>

    <div class="join-future-content py-3 container">
      <div class="future-text">
        <p>Web3 isn’t just the future</p>
        <span class="future-text-gradient">it’s YOUR future.</span>
      </div>
      <div class="vector-img">
        <img src="/img/Vector 17.png" class="img-fluid" alt="">
      </div>
      <div class="d-flex justify-content-center mt-2">
        <button class="btn join-btn">Become a Partner</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.join-future-section{
  background: #1F1F1F;
  position: relative;
}
.join-bg-img{
  position: absolute;
  top: 0;
  right: 0;
}

.future-text{
  font-family: Neulis Alt;
    font-size: 48px;
    font-weight: 600;
    line-height: 56.6px;
    letter-spacing: -0.01em;
    text-align: center;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
}

.future-text-gradient{
  background: linear-gradient(91.25deg, #026F7E -1%, #0DFD7E 164.59%) !important;
    background-clip: text !important;
    -webkit-text-fill-color: transparent;
}

.vector-img{
  text-align: center !important;
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

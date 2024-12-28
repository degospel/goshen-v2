<template>
  <div class="container hero-img-section">
    <div class="hero-img">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="/img/image_fx_ (59) 2.png" class="img-fluid rounded-start-4" alt="">
        </div>
        <div class="col-md-4">
          <img src="/img/image_fx_ (8) 2.png" class="img-fluid" alt="">
        </div>
        <div class="col-md-4">
          <img src="/img/image_fx_ (5) 2.png" class="img-fluid rounded-end-4" alt="">
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
.hero-img-section{
  position: relative;
  width: 100%;
  height: 300px;
  margin-bottom: 5rem !important;
}

.hero-img{
  position: absolute;
  top: -100px !important;
  height: 100% !important;
}

.img-fluid{
  height: 100% !important;
  width: 100% !important;
  object-fit: cover;
}

@media (max-width: 768px) {
  .hero-img-section{
    position: static !important;
    height: 100% !important;
  }

  .hero-img{
    position: static !important;
    top: 0 !important;
  }

}
</style>


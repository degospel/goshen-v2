<template>
  <div class="about-hero">
    <div class="section-content about-body mt-5">
      <div class="about-content text-center container py-3 mt-5">
        <p class="text-gradient">About Us</p>
      </div>

      <div class="container-fluid vision-mission">

        <div class="vision-mission-img">
          <img src="/img/Ellipse 16.png" alt="">
        </div>
        <div class="container">
          <div class="row justify-content-center py-5">
            <div class="col-md-6">
              <div class="card p-4">
                <div class="card-body">
                  <h5 class="card-title">Our Mission</h5>
                  <p class="card-text">
                    Our mission is to provide non-technical talents, not just developers with all they need to
                    understand and grow in Web3 through content, communities, and opportunities. We’re providing talents
                    and creatives in Web3 with necessary resources and tools.
                  </p>
                </div>
              </div>
            </div>

            <div class="col-md-6">
              <div class="card card-2 p-4">
                <div class="card-body">
                  <h5 class="card-title">Our Vision</h5>
                  <p class="card-text">
                    We believe that anyone regardless of technical skills should access Web3. Our goal, therefore, is to
                    become the leading platform for non-technical talents and creatives to grow and thrive in Web3.
                    Hence, Goshen is the bridge connecting non-technical talents to Web3.
                  </p>
                </div>
              </div>
            </div>
          </div>
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
.about-hero {
  position: relative !important;
  height: 100vh;
  width: 100%;
  background: url('/img/Ellipse 2.png') no-repeat center;
}

.about-body{
  position: absolute !important;
  top: 50% !important;
  left: 50% !important;
  transform: translate(-50%, -50%) !important;
  width: 100%;
  /* height: 100%; */
}

.vision-mission{
  background: #1F1F1F;
  position: relative;
}

.vision-mission-img{
  position: absolute;
  right: 0;
}

.card{
  background: #2c2c2c !important;
  color: #fff;
}
.card-2 {
  background: #0DFD7E12 !important;
  color: #fff;
}

.card-title{
  font-size: 32px;
  font-weight: 500;
  line-height: 36px;
  text-align: left;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.card-text{
  font-size: 21px;
  font-weight: 300;
  line-height: 32px;
  text-align: left;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}
</style>

<template>
  <div>
    <section class="hero-section container-fluid">
      <div class="hero-body text-center container">
        <div class="hero-content">
          <p class="hero-big-text">Web3 For Everyone</p>
          <span class="linear-text-big">Not Just Developers</span>

          <div>
            <p>Connecting non-technical talents to Web3 through tailored content, communities and opportunities.</p>
          </div>
        </div>

        <div class="hero-button d-grid gap-2 d-md-block mt-5">
          <button class="btn me-md-3 join-btn">Join Academy</button>
          <button class="btn me-md-3 join-btn">Become a Partner</button>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.hero-section{
  position: relative !important;
  height: 100vh;
  width: 100%;
  background: url('/img/Ellipse 2.png') no-repeat center;
}

.hero-body{
  position: absolute !important;
  top: 50% !important;
  left: 50% !important;
  transform: translate(-50%, -50%) !important;
  width: 70%;
  /* height: 50%; */
}

.hero-content .hero-big-text{
  font-size: 64px;
  font-weight: 600;
  line-height: 70.5px;
}

.hero-content .linear-text-big{
  font-size: 64px;
  font-weight: 600;
  line-height: 70.5px;
  background: linear-gradient(91.25deg, #026F7E -5.44%, #0DFD7E 164.59%);
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

.join-btn {
  background: #026F7E !important;
  border: 1px solid #026F7E;
  border-radius: 12px;
  padding: 10px 20px !important;
  text-transform: capitalize;
  color: #fff;
}


@media (max-width: 768px) {
  .hero-content .hero-big-text{
    font-size: 34px !important;
    font-weight: 600;
    line-height: 30.5px;
  }

  .hero-content .linear-text-big{
    font-size: 34px;
    font-weight: 600;
    line-height: 30.5px;
    background: linear-gradient(91.25deg, #026F7E -5.44%, #0DFD7E 164.59%);
    background-clip: text;
    -webkit-text-fill-color: transparent;
  }

  .hero-body{
    width: 100%;
    /* height: 50%; */
  }

  .hero-button{
    margin-top: 1rem !important;
  }
}
</style>

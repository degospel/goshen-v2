<template>
  <div>
    <Navbar />
    <nuxt />
    <Footer/>
  </div>
</template>

<script>
import Navbar from "~/layouts/partials/navbar.vue"
import Footer from "~/layouts/partials/footer.vue"
export default {
  components: {
    Navbar,
    Footer
  }
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Neulis Alt' !important;
  color: #fff !important;
  background: #1A1A1A !important;
  width: 100%;
}

p{
  margin: 0 !important;
}

.section-header-big {
  font-size: 56px;
  font-weight: 600;
  line-height: 61.6px;
  letter-spacing: -0.01em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.section-header{
  font-size: 48px;
  font-weight: 500;
  line-height: 62.64px;
  letter-spacing: -0.01em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.section-header-small {
  font-size: 48px;
  font-weight: 400;
  line-height: 62.64px;
  letter-spacing: -0.01em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.section-header-smaller {
  font-size: 40px;
  font-weight: 400;
  line-height: 40.64px;
  letter-spacing: -0.01em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.section-span{
  font-size: 16px;
  font-weight: 300;
  line-height: 20.88px;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.text-gradient{
  background: linear-gradient(91.25deg, #026F7E -5.44%, #0DFD7E 164.59%) !important;
  background-clip: text !important;
  -webkit-text-fill-color: transparent;

  font-size: 56px;
  font-weight: 400;
  line-height: 61.6px;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}


/* @media (max-width: 468px) {

} */

@media (max-width: 768px) {
  .section-header{
    font-size: 38px;
    font-weight: 500;
    line-height: 42.64px;
    letter-spacing: -0.01em;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
  }

  .section-header-big {
    font-size: 40px;
    font-weight: 600;
    line-height: 40.6px;
    letter-spacing: -0.01em;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
  }

  .section-header-small {
    font-size: 40px;
    font-weight: 400;
    line-height: 40.64px;
    letter-spacing: -0.01em;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
  }

  .section-header-smaller {
    font-size: 30px;
    font-weight: 400;
    line-height: 35.64px;
    letter-spacing: -0.01em;
    text-underline-position: from-font;
    text-decoration-skip-ink: none;
  }
}
</style>

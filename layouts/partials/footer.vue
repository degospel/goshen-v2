<template>
  <div class="footer-section">
    <footer class="container">
      <div class="pt-5">
        <div class="row">
          <div class="col-md-4 col-sm-12 mb-3">
            <div>
              <img src="/img/logo.png" alt="">
            </div>

            <div>
              <span>Web3 for everybody not just developers</span>
            </div>

            <div class="footer-socials mt-3 d-flex align-items-center">
              <div class="socials-body">
                <i class="bi bi-linkedin icon-bg"></i>
              </div>
              <div class="socials-body">
                <i class="bi bi-instagram"></i>
              </div>
              <div class="socials-body">
                <i class="bi bi-twitter-x"></i>
              </div>
            </div>
          </div>
          <div class="col-md-2 col-sm-6 col-6 p-0 float-left mb-3">
            <h5 class="mb-4 font-weight-bold text-uppercase">Company</h5>
            <ul class="list-group">
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Home</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">About Us</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Contact Us</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="col-md-2 col-sm-6 col-6 p-0 mb-3 float-left">
            <h5 class="mb-4 font-weight-bold text-uppercase">Learn</h5>
            <ul class="list-group">
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Courses</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Community</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Partner</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="col-md-2 col-sm-6 col-6 p-0 mb-3 float-left">
            <h5 class="mb-4 font-weight-bold text-uppercase">Reasources</h5>
            <ul class="list-group">
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Blog</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Glossary</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="col-md-2 col-sm-6 col-6 p-0 mb-3 float-left">
            <h5 class="mb-4 font-weight-bold text-uppercase">Legal</h5>
            <ul class="list-group">
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Privacy Policy</nuxt-link>
              </li>
              <li class="list-group-item bg-transparent border-0 p-0 mb-2">
                <nuxt-link to="/">Terms & Conditions</nuxt-link>
              </li>
            </ul>
          </div>

          <div class="col-md-12 mt-5">
            <div class="py-4 d-flex justify-content-center align-items-center">
              © {{currentDate.getFullYear()}} Goshen.academy - All Rights Reserved
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  data(){
    return {
      currentDate: new Date,
    }
  }
}
</script>

<style scoped>
h5 {
  font-size: 1rem;
  line-height: 1.375;
  font-weight: 500;
  color: #A8A6A6;
}

a {
  color: #fff;
  font-weight: 400;
  text-decoration: none;
  background-color: transparent;
}

a:hover {
  color: #026F7E;
  text-decoration: none;
}

.footer-section {
  background: #1F1F1F;
}


.socials-body {
  color: #CBFFEC;
  font-size: 16px;
  margin-right: 15px;
  height: 40px !important;
    width: 40px !important;
    text-align: center;
    line-height: 38px;
    border-radius: 50%;
    background: #026F7E;
}

.bi::before{
  line-height: 0 !important;
}

/* .socials-body i{
  height: 40px !important;
  width: 40px !important;
  text-align: center;
  line-height: 38px;
  border-radius: 50%;
} */

</style>

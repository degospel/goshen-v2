<template>
  <div>
    <nav class="navbar mt-4 navbar-expand-lg">
      <div class="container nav">
        <a class="logo" href="#">
          <img src="/img/logo.png" alt="">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <nuxt-link class="nav-link active" aria-current="page" to="/">Home</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/community">Community</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/partner">Partner</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/about">About Us</nuxt-link>
            </li>
          </ul>

          <ul class="navbar-nav">
            <li class="nav-item">
              <button class="nav-link join-btn">Join Academy</button>
            </li>

            <li class="nav-item">
              <button class="nav-link login-btn">Login</button>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>

</script>

<style scoped>

.navbar{
  position: fixed !important;
  top: 0;
  width: 100%;
  transition: background-color 0.3s ease;
  z-index: 10;
}

.nav{
  padding: 1rem !important;
    border: 1px solid transparent;
    border-radius: 40px !important;
    background: #1F1F1F0D !important;
    border-bottom: 1px solid #1F1F1F !important;
    backdrop-filter: blur(40px);
-webkit-backdrop-filter: blur(40px);
  /* margin: 0 auto !important; */
}

.navbar .navbar-nav .nav-item > a {
  position: relative !important;
}

.nav-underline{
  color: #026F7E !important;
  border-bottom-color: #026F7E !important;
}

.navbar .navbar-nav .nav-item > a.active{
  color: #A8A6A6 !important;
}

.navbar .navbar-nav .nav-item > a.active::before{
  content: "";
  width: 100% !important;
  position: absolute !important;
  bottom: 0;
  left: 0;
  height: 2px !important;
  background: #026F7E !important;
  color: #A8A6A6 !important;
}

.nav-link{
  color: #A8A6A6;
  margin-left: .80rem !important;
}

.join-btn{
  background: #026F7E !important;
  border: 1px solid #026F7E;
  border-radius: 12px;
  padding: 10px 20px !important;
  text-transform: capitalize;
}

.login-btn{
  background: transparent !important;
  border: 1px solid #fff;
  border-radius: 12px;
  text-transform: capitalize;
  padding: 10px 30px !important;
}
</style>

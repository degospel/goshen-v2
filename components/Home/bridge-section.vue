<template>
  <div class="Bridge-section container">
    <div class="Section-content py-3">
      <div class="text-center ">
        <p class="section-header">Your Bridge To Web3</p>
        <span class="section-span">Goshen helps non-technical talents and creatives grow in Web3—no coding
          required.</span>
      </div>

      <div class="">
        <div class="justify-content-center d-grid">
          <ul class="nav nav-pills rounded-5 my-4 " id="pills-tab" role="tablist">
            <li class="nav-item" role="presentation">
              <button id="pills-home-tab" class="nav-link active rounded-5" data-bs-toggle="pill"
                data-bs-target="#pills-home" type="button" role="tab" aria-controls="pills-home"
                aria-selected="true">Content</button>
            </li>
            <li class="nav-item" role="presentation">
              <button class="nav-link rounded-5" id="pills-profile-tab" data-bs-toggle="pill"
                data-bs-target="#pills-profile" type="button" role="tab" aria-controls="pills-profile"
                aria-selected="false">Communities</button>
            </li>
            <li class="nav-item" role="presentation">
              <button class="nav-link rounded-5" id="pills-contact-tab" data-bs-toggle="pill"
                data-bs-target="#pills-contact" type="button" role="tab" aria-controls="pills-contact"
                aria-selected="false">Opportunities</button>
            </li>
          </ul>
        </div>
        <div class="tab-content" id="pills-tabContent">
          <div class="tab-pane fade show active" id="pills-home" role="tabpanel" aria-labelledby="pills-home-tab"
            tabindex="0">
            <div class="nav-cards">

              <div class="card p-3 mb-3">
                <div class="row align-items-center">
                  <div class="col-md-8">
                    <div class="card-body">
                      <div class="img-icon">
                        <img src="/img/content-home.png" class="img-fluid" alt="">
                      </div>
                      <h5 class="card-title">Content</h5>
                      <p class="card-text">Leverage resources to build your non-technical skills in Web3. Gain access
                        to courses, events, and resources to build your career.
                      </p>
                    </div>
                  </div>

                  <div class="col-md-4">
                    <img src="/img/Frame 1091.png" class="img-fluid" alt="...">
                  </div>
                </div>
              </div>

            </div>
          </div>
          <div class="tab-pane fade" id="pills-profile" role="tabpanel" aria-labelledby="pills-profile-tab"
            tabindex="0">
            <div class="nav-cards">

              <div class="card p-3 mb-3">
                <div class="row align-items-center">
                  <div class="col-md-8">
                    <div class="card-body">
                      <div class="img-icon">
                        <img src="/img/communities-badge.png" class="img-fluid" alt="">
                      </div>
                      <h5 class="card-title">Communities</h5>
                      <p class="card-text">Communities
                        Find your tribe in Web3. Join our growing network of Web3 communities and connect with other
                        non-technical talents.
                      </p>
                    </div>
                  </div>

                  <div class="col-md-4">
                    <img src="/img/Frame 1092.png" class="img-fluid" alt="...">
                  </div>
                </div>
              </div>

            </div>
          </div>
          <div class="tab-pane fade" id="pills-contact" role="tabpanel" aria-labelledby="pills-contact-tab"
            tabindex="0">
            <div class="nav-cards">

              <div class="card p-3 mb-3">
                <div class="row align-items-center">
                  <div class="col-md-8">
                    <div class="card-body">
                      <div class="img-icon">
                        <img src="/img/oppourtunite-badge.png" class="img-fluid" alt="">
                      </div>
                      <h5 class="card-title">Opportunities</h5>
                      <p class="card-text">
                        Access opportunities and thrive in Web3 as a non-technical talent. Gain valuable skills and
                        contribute to the ecosystem.
                      </p>
                    </div>
                  </div>

                  <div class="col-md-4">
                    <img src="/img/Frame 1093.png" class="img-fluid" alt="...">
                  </div>
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
.nav-pills .nav-item .active{
  background-color: #026F7E !important;
  color: #fff !important;
}

.nav-pills {
  background-color: #1F1F1F !important;
  padding: .20rem;
  color: #fff !important;
}

.nav-link{
  color: #fff !important;
}

.card{
  background: #161616 !important;
  color: #CACACA !important;
}

.card-body{
  width: 90% !important;
}

.img-icon{
  width: 56px !important;
  height: 56px !important;
  margin-bottom: 1rem;
}

.card-title{
  font-size: 24px;
  font-weight: 600;
  line-height: 36px;
  letter-spacing: -0.01em;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.card-text{
  font-size: 16px;
  font-weight: 300;
  line-height: 28px;
  letter-spacing: -0.01em;
  text-align: left;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}
</style>

<template>
  <div class="testimonial-section container">
    <div class="Section-content py-3">
      <div class="text-center">
        <p class="section-header">
          What our students say!
        </p>
        <span class="section-span">See what people are saying about our workshops and courses.</span>
      </div>

      <div class="row justify-content-center">
        <div id="carouselExampleDark" class="carousel carousel-dark slide carousel-fade" data-bs-ride="carousel">
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
              aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
              aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2"
              aria-label="Slide 3"></button>
          </div>
          <div class="carousel-inner text-center py-5 d-grid justify-content-center">
            <div class="carousel-item active py-5" data-bs-interval="2000">
              <div class="stack-container">
                <div class="card card-red"></div>
                <div class="card card-blue"></div>
                <div class="card card-green">

                  <div class="carousel-body">
                    <div class="quote">
                      <p>
                        “The workshop sparked my interest in the field, and I am now ready to pursue a career in  Web3 marketing”
                      </p>
                    </div>

                    <div>
                      <div class="num-circle">
                        <p>FO</p>
                      </div>

                      <div class="name-details">
                        <p>Folakemi Orekoya</p>
                        <span>Workshop Attendee</span>
                      </div>
                    </div>
                  </div>

                </div>
              </div>
            </div>


            <div class="carousel-item py-5" data-bs-interval="2000">
              <div class="stack-container stack-2">
                <div class="card card-red"></div>
                <div class="card card-blue"></div>
                <div class="card card-yellow"></div>
                <div class="card card-green">

                  <div class="carousel-body">
                    <div class="quote">
                      <p>
                        “ I liked how the instructor explained Web3. It always felt complex, but learning it live made it much easier to understand.”
                      </p>
                    </div>

                    <div>
                      <div class="num-circle-2">
                        <p>OO</p>
                      </div>

                      <div class="name-details details-2">
                        <p>Oyinloluwa Ola-Obaado</p>
                        <span>Workshop Attendee</span>
                      </div>
                    </div>
                  </div>

                </div>
              </div>
            </div>

            <div class="carousel-item py-5" data-bs-interval="2000">
              <div class="stack-container">
                <div class="card card-red"></div>
                <div class="card card-blue"></div>
                <div class="card card-green">

                  <div class="carousel-body">
                    <div class="quote">
                      <p>
                        “The design thinking approach to Web3 stood out. Although I use DApps often, I never considered exploring the space until now.”
                      </p>
                    </div>

                    <div>
                      <div class="num-circle">
                        <p>JA</p>
                      </div>

                      <div class="name-details">
                        <p>Joshua Abodunwa</p>
                        <span>Workshop Attendee</span>
                      </div>
                    </div>
                  </div>

                </div>
              </div>
            </div>
          </div>
          <!-- <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button> -->
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
.carousel-item{
  width: 400px;
  height: 500px;
}

.carousel-indicators{
  /* position: relative; */
  bottom: 90px;
}

.carousel-indicators [data-bs-target]{
  height: 10px;
  width: 10px;
  border-radius: 50%;
}

/* .carousel-dark .carousel-indicators [data-bs-target]{
  background-color: #CBFFEC;
} */

/* Stack container */
.stack-container {
  position: relative;
  width: 100%;
  height: 100%;
  perspective: 1000px;
}

/* Cards */
.card {
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transform-origin: center;
  transition: transform 0.5s ease;
}

/* Individual card styles */
.card-red {
  background-color: #0E0E0E;
  transform: rotate(-7deg) translateY(20px);
  z-index: 1;
}

.card-blue {
  background-color: #01637E1C;
  transform: rotate(10deg) translateY(10px);
  z-index: 2;
}

.card-green {
  background-color: #026F7E;
  transform: rotate(0deg);
  z-index: 3;
}

/* Stack 2 */
.stack-2 .card-red {
  background-color: #0E0E0E;
  transform: rotate(-7deg) translateY(20px);
  z-index: 1;
}

.stack-2 .card-blue {
  background-color: #01637E1C;
  transform: rotate(10deg) translateY(10px);
  z-index: 2;
}

.stack-2 .card-yellow {
  background-color: #026F7E70;
  transform: rotate(4.55deg) translateY(10px);
  z-index: 2;
}

.stack-2 .card-green {
  background-color: #CBFFEC;
  transform: rotate(0deg);
  z-index: 3;
}

.carousel-body{
  height: 100%;
  width: 100%;
  background: url("../../static/img/Ribbon-2.png") no-repeat center;
  background-size: contain;
  color: #FFFFFF;
  padding: 1rem 2rem !important;
  display: grid;
  justify-content: center;
  align-items: center;
}

.stack-2 .carousel-body{
  color: #000;
}

.quote p{
  font-family: Neulis Alt;
  font-size: 20px;
  font-weight: 400;
  line-height: 36px;
  letter-spacing: -0.03em;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.num-circle{
  background: #FFFFFF;
  color: #000;
  border-radius: 50%;
  display: table;
  height: 64px;
  font-weight: 400;
  font-size: 20px;
  width: auto;
  margin: .75rem auto;
}

.num-circle-2{
  background: #026F7E;
  color: #fff;
  border-radius: 50%;
  display: table;
  height: 64px;
  font-weight: 400;
  font-size: 20px;
  width: auto;
  margin: .75rem auto;
}

.num-circle-2 p{
  display: table-cell;
  vertical-align: middle;
  height: 64px;
  width: 64px;
  text-align: center;
  padding: 0 15px;
}

.num-circle p{
  display: table-cell;
  vertical-align: middle;
  height: 64px;
  width: 64px;
  text-align: center;
  padding: 0 15px;
}

.name-details p{
  font-size: 20px;
  font-weight: 500;
  line-height: 26.1px;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.name-details span{
  font-size: 14px;
  font-weight: 400;
  line-height: 18.27px;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}

.details-2{
  color: #026F7E;
}
</style>

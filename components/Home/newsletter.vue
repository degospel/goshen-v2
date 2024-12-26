<template>
  <div class="newletter-section container-fluid py-3">

    <div class="newletter-bg-img">
      <img src="/img/Ellipse 3.png" class="img-fluid" alt="">
    </div>

    <div class="section-content py-5 container">
      <div class="text-center">
        <p class="section-header">
          Join our Newsletter
        </p>
        <span class="section-span">Discover the latest updates, opportunities and resources in your inbox weekly</span>
      </div>

      <div class="letter-email">
        <div class="row vertical-center">
          <div class="col-md-12">
            <form>
              <div class="input-group mb-3">

                <input type="email" class="form-control" placeholder="Enter your email address"
                  aria-label="Example text with button addon" aria-describedby="button-addon1">
                <button class="btn" type="button" id="button-addon1">Subscribe now</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>


    <div class="newletter-bg-img-right">
      <img src="/img/Ellipse 4.png" alt="">
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.newletter-section{
  position: relative;
}

.newletter-bg-img{
  position: absolute;
  top: -550px;
  left: 0;
}

.newletter-bg-img-right{
  position: absolute;
  top: -200px;
  /* left: 0; */
  right: 0;
  bottom: 0;
  /* overflow: hidden; */
}

.newletter-bg-img-right img{
  /* height: 400px; */
  /* transform: rotate(-139deg); */
  overflow: hidden !important;
  object-fit: contain;
}

.letter-email{
  /* width: 100% !important; */
  /* height: 100% !important; */
  display: flex;
  align-items: center;
  justify-content: center !important;
  margin-top: 2.5rem !important;
}

.input-group{
  width: 100% !important;
}

form .form-control:focus {
  box-shadow: none !important;
  outline: none !important;
}

form .form-control::placeholder {
  color: #FFFFFF85 !important;
  font-size: 14px !important;
}

form .form-control {
  box-shadow: none !important;
  outline: none !important;
  background: transparent !important;
  color: #ffffffe1;
  border: 1px solid #FFFFFF61;
  border-radius: 0px !important;
}

form .input-group .btn{
  color: #CBFFEC;
  background: #026F7E !important;
  border: 1px solid #FFFFFF61;
  border-radius: 0px !important;
}
</style>

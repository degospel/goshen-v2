<template>
  <div class="join-us-section">
    <div class="join-us-content container">
      <div class="join-us-body text-center">
        <div class="section-header-small py-4">
          <p>Why Join Us?</p>
        </div>


        <div>
          <div class="row">
            <div class="col-md-3">
              <div class="num-circle">
                <p>1.</p>
              </div>

              <div class="num-text">
                <p>
                  Connect with other Web3 enthusiasts and experts with the same interests
                </p>
              </div>
            </div>

            <div class="col-md-3">
              <div class="num-circle">
                <p>2.</p>
              </div>

              <div class="num-text">
                <p>
                  A collaborative space for learning, discussion and networking
                </p>
              </div>
            </div>

            <div class="col-md-3">
              <div class="num-circle">
                <p>3.</p>
              </div>

              <div class="num-text">
                <p>
                  Get exclusive updates on new courses and upcoming events.
                </p>
              </div>
            </div>

            <div class="col-md-3">
              <div class="num-circle">
                <p>4.</p>
              </div>

              <div class="num-text">
                <p>
                  Mini support groups and interactive channels with mentors
                </p>
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
.join-us-body{
  position: relative;
  top: -150px;
}

.num-circle{
  background: #026F7E;
  border-radius: 50%;
  display: table;
  height: 40px;
  font-weight: bold;
  font-size: 1.2em;
  width: auto;
  margin: .75rem auto;
}

.num-circle p{
  display: table-cell;
  vertical-align: middle;
  height: 40px;
  width: 40px;
  text-align: center;
  padding: 0 15px;
}

.num-text{
  font-size: 18px;
  font-weight: 400;
  line-height: 23.49px;
  text-align: center;
  text-underline-position: from-font;
  text-decoration-skip-ink: none;
}
</style>

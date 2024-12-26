<template>
  <div class="Faqs-section container">
    <div class="Section-content py-5">
      <div class="row">
        <div class="col-md-4">
          <div>
            <p class="section-header">FAQs</p>
            <span>Do you still have questions about Goshen?</span>
          </div>
        </div>

        <div class="col-md-8">

          <div class="accordion" id="accordionExample">
            <div class="accordion-item  mb-3">
              <h2 class="accordion-header">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne"
                  aria-expanded="true" aria-controls="collapseOne">
                  What is Goshen Academy? 
                </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  Goshen connects non-technical talents with everything they need to grow in Web3. Hence, Web3 for
                  everyone—not just developers
                </div>
              </div>
            </div>
            <div class="accordion-item mb-3">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  I am a complete newbie, can I join Goshen Academy?
                </button>
              </h2>
              <div id="collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  Definitely! Goshen was built for everyone, including beginners. Our range of resources will help you
                  understand Web3 basics, and take you through becoming a Web3 expert.
                </div>
              </div>
            </div>
            <div class="accordion-item mb-3">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                  How do I start learning?
                </button>
              </h2>
              <div id="collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  Start learning by clicking on “Explore Academy” on the top of the screen.
                </div>
              </div>
            </div>
            <div class="accordion-item mb-3">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapseFour" aria-expanded="false" aria-controls="collapseFour">
                  What courses can I learn at Goshen Academy?
                </button>
              </h2>
              <div id="collapseFour" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  Goshen Academy is focused on non-technical skills in Web3 such as Design, Marketing, Product
                  Management, Community Management, Content Writing etc.
                </div>
              </div>
            </div>
            <div class="accordion-item mb-3">
              <h2 class="accordion-header">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                  data-bs-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                  Where can I get help?
                </button>
              </h2>
              <div id="collapseFive" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  If you need any help, feel free to join our growing community here: bit.ly/Goshencommunity
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

.accordion-button:focus {
  box-shadow: none !important;
}

.accordion-item{
  background-color: #181F21 !important;
  color: #fff !important;
  border: 1px solid #181F21 !important;
  border-top-left-radius: 10px !important;
  border-top-right-radius: 10px !important;
  border-bottom-left-radius: 10px !important;
  border-bottom-right-radius: 10px !important;
  /* border-color: #53fe12 !important; */
  /* border-radius: 10px !important; */
}

.accordion-button {
  background-color: #181F21 !important;
  color: #fff !important;
  /* border: 1px solid #fff !important; */
  border-top-left-radius: 10px !important;
  border-top-right-radius: 10px !important;

  border-bottom-left-radius: 10px !important;
    border-bottom-right-radius: 10px !important;
  box-shadow: none !important;
  /* border-radius: 10px !important; */

}

.accordion-button::after {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
}

.accordion-button.collapsed::after {
  background-image: url("data:image/svg+xml,%3csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16' fill='%23fff'%3e%3cpath fill-rule='evenodd' d='M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z'/%3e%3c/svg%3e");
}

.accordion-button.open{
  border: 1px solid yellow !important;
}

.accordion-button:not(.collapsed) {
  background-color: #026F7E !important;
  box-shadow: none !important;
  border-bottom-left-radius: 0 !important;
  border-bottom-right-radius: 0 !important;
}

.accordion-collapse {
  background-color: #026F7E!important;
  border-bottom-left-radius: 10px !important;
  border-bottom-right-radius: 10px !important;
}
</style>

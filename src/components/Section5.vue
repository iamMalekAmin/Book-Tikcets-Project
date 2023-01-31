<template>
       <section class="pricing-section section-padding section-bg" id="section_5">
                <div class="container">
                    <div class="row">

                        <div class="col-lg-8 col-12 mx-auto">
                            <h2 class="text-center mb-4">Plans, you' love</h2>
                        </div>
                        
                        <div class="col-lg-6 col-12">
                            <div class="pricing-thumb">
                                <div class="d-flex">
                                    <div>
                                        <h3>Early Bird $120</h3>

                                        <p>Including good things:</p>
                                    </div>

                                    <p class="pricing-tag ms-auto">Save up to <span>50%</span></p>
                                </div>

                                <ul class="pricing-list mt-3">
                                    <li class="pricing-list-item">platform for potential customers</li>

                                    <li class="pricing-list-item">digital experience</li>



                                    <li class="pricing-list-item">standard content</li>
                                </ul>

                                <a class="link-fx-1 color-contrast-higher mt-4" href="#">
                                    <span>Buy Ticket</span>
                                    <svg class="icon" style="width: 20px; padding-left: 5px;" viewBox="0 0 32 32" aria-hidden="true"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><circle cx="16" cy="16" r="15.5"></circle><line x1="10" y1="18" x2="16" y2="12"></line><line x1="16" y1="12" x2="22" y2="18"></line></g></svg>
                                </a>
                            </div>
                        </div>

                        <div class="col-lg-6 col-12 mt-4 mt-lg-0">
                            <div class="pricing-thumb">
                                <div class="d-flex">
                                    <div>
                                        <h3>Standard $240</h3>

                                        <p>What makes a premium MA Tickets?</p>
                                    </div>
                                </div>

                                <ul class="pricing-list mt-3">

                                    <li class="pricing-list-item">digital experience</li>

                                    <li class="pricing-list-item">premium content</li>
                                    
                                    <li class="pricing-list-item">live chat support</li>
                                </ul>

                                <a class="link-fx-1 color-contrast-higher mt-4" href="#">
                                    <span>Buy Ticket</span>
                                    <svg class="icon" style="width: 20px; padding-left: 5px;" viewBox="0 0 32 32" aria-hidden="true"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"><circle cx="16" cy="16" r="15.5"></circle><line x1="10" y1="18" x2="16" y2="12"></line><line x1="16" y1="12" x2="22" y2="18"></line></g></svg>
                                </a>
                            </div>
                        </div>

                    </div>
                </div>
            </section>


</template>


<style scoped>

h2{
    font-size: 52px;
    font-weight: 700;
}
h3{
    font-size: 38px;
    font-weight: 600;
}
.section-padding {
  padding-top: 100px;
  padding-bottom: 100px;
}

.section-bg {
  background-color: #f0f8ff;
}


.section-overlay + .container {
  position: relative;
}




.pricing-thumb {
  border: 5px dotted black;
  border-radius: 20px;
  position: relative;
  padding: 50px;
}

.pricing-thumb h3 small {
  display: inline-block;
  font-size: 18px;
  margin-right: 15px;
}

.pricing-list {
  column-count: 2;
  padding-left: 20px;
}

.pricing-list-item {
  line-height: normal;
  margin-right: 10px;
  margin-bottom: 10px;
}

.pricing-tag {
  background-color:  #EE5007;
  border-radius: 100px;
  color: #ffffff;
  font-weight: 700;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 120px;
  height: 120px;
  position: absolute;
  top: 0;
  right: 0;
  margin: 20px;
}

.pricing-tag span {
  font-size: 180%;
  line-height: normal;
}

.pricing-thumb .link-fx-1 {
  color:  #F8CB2E;
}

.pricing-thumb .link-fx-1:hover {
  color: #B22727;
}


</style>
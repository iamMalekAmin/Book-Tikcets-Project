<template>
                <section class="about-section section-padding" id="section_2">
                <div class="container">
                    <div class="row">

                        <div class="col-lg-6 col-12 mb-4 mb-lg-0 d-flex align-items-center">
                            <div class="services-info">
                                <h2 class="text-white mb-4">About MA Tickets 2023</h2>

                                <p class="text-white">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Assumenda commodi sapiente reiciendis dolor voluptatem veritatis quam blanditiis molestias omnis ullam.</p>

                                <h3 class="text-white mt-4">Lorem ipsum dolor sit</h3>

                                <p class="text-white">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nulla, ea?</p>

                                <h3 class="text-white mt-4">Lorem, ipsum dolor</h3>

                                <p class="text-white">Please tell your friends about our website. Thank you.</p>
                            </div>
                        </div>

                        <div class="col-lg-6 col-12">
                            <div class="about-text-wrap">
                                <img src="./images/hall.jpeg" class="about-image img-fluid">

                                <div class="about-text-info d-flex">
                                    <div class="d-flex">
                                        <i class="about-text-icon bi-person"></i>
                                    </div>


                                    <div class="ms-4">
                                        <h3>a happy moment</h3>

                                        <p class="mb-0">your amazing celebration moment with us</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </section>
</template>


<style scoped>


.section-padding {
  padding-top: 100px;
  padding-bottom: 100px;
}





.about-section {
  background-image: url('./images/edward-unsplash-blur.jpg');
  background-color: #704010;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

h2{
    font-size: 52px;
    font-weight: 800;
}

.about-image {
  border-radius: 20px;
  display: block;
}

.about-text-wrap {
  position: relative;
}

.about-text-icon {
  background: #F8CB2E;
  border-radius: 100%;
  font-size: 32px;
  width: 70px;
  height: 70px;
  line-height: 70px;
  text-align: center;
}

.about-text-info {
  backdrop-filter: blur(5px) saturate(180%);
  -webkit-backdrop-filter: blur(5px) saturate(180%);
  background-color: rgba(255, 255, 255, 0.75);
  border-radius: 20px;
  border: 1px solid rgba(209, 213, 219, 0.3);
  position: absolute;
  bottom: 0;
  right: 0;
  left: 0;
  margin: 20px;
  padding: 35px;
}
</style>
<template>
     <section class="contact-section section-padding" id="section_6">
                <div class="container">
                    <div class="row">

                        <div class="col-lg-8 col-12 mx-auto">
                            <h2 class="text-center mb-4">Interested? Let's talk</h2>

                            <nav class="d-flex justify-content-center">
                                <div class="nav nav-tabs align-items-baseline justify-content-center" id="nav-tab" role="tablist">
                                    <button class="nav-link active" id="nav-ContactForm-tab" data-bs-toggle="tab" data-bs-target="#nav-ContactForm" type="button" role="tab" aria-controls="nav-ContactForm" aria-selected="false">
                                        <h5>Contact Form</h5>
                                    </button>
                                </div>
                            </nav>

                            <div class="tab-content shadow-lg mt-5" id="nav-tabContent">
                                <div class="tab-pane fade show active" id="nav-ContactForm" role="tabpanel" aria-labelledby="nav-ContactForm-tab">
                                    <form class="custom-form contact-form mb-5 mb-lg-0" action="#" method="post" role="form">
                                        <div class="contact-form-body">
                                            <div class="row">
                                                <div class="col-lg-6 col-md-6 col-12">
                                                    <input type="text" name="contact-name" id="contact-name" class="form-control" placeholder="Full name" required>
                                                </div>

                                                <div class="col-lg-6 col-md-6 col-12">
                                                    <input type="email" name="contact-email" id="contact-email" pattern="[^ @]*@[^ @]*" class="form-control" placeholder="Email address" required>
                                                </div>
                                            </div>

                                            <input type="number" name="contact-company" id="contact-company" class="form-control" placeholder="phone" required >

                                            <textarea name="contact-message" rows="3" class="form-control" id="contact-message" placeholder="Message"></textarea>

                                            <div class="col-lg-4 col-md-10 col-8 mx-auto">
                                                <button type="submit" class="form-control">Send message</button>
                                            </div>
                                        </div>
                                    </form>
                                </div>

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

.section-padding {
  padding-top: 100px;
  padding-bottom: 100px;
}

.tab-content {
  background-color: #fff;
  border-radius: 20px;
  padding: 45px;
}

.nav-tabs {
  background-color: #f0f8ff;
  border-radius: 100px;
  border-bottom: 0;
  padding: 15px;
}

.nav-tabs .nav-link {
  border-radius: 100px;
  border: 0;
  padding: 15px 25px;
  transition: all 0.3s;
}



.nav-tabs .nav-item.show .nav-link, 
.nav-tabs .nav-link.active,
.nav-tabs .nav-link:focus, 
.nav-tabs .nav-link:hover {
  background: #fff;
  box-shadow: 0 1rem 3rem rgba(0,0,0,.175);
  color:  #F8CB2E;
  cursor: default;
}

.nav-tabs h5 {
  color: #717275; 
  margin-bottom: 0;
}

.nav-tabs .nav-link.active h5,
.nav-tabs .nav-link:focus h5, 
.nav-tabs .nav-link:hover h5 {
  color: #F8CB2E;
}





.custom-form .form-control {
  color:  #717275;
  margin-bottom: 24px;
  padding-top: 13px;
  padding-bottom: 13px;
  outline: none;
}

.custom-form button[type="submit"] {
  background:  #EE5007;
  border: none;
  border-radius: 100px;
  color: #ffffff;
  font-size: 18px;
  font-weight: 400;
  transition: all 0.3s;
  margin-bottom: 0;
}

.custom-form button[type="submit"]:hover,
.custom-form button[type="submit"]:focus {
  background: #c01f27;
  border-color: transparent;
}

</style>
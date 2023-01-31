
<template>
      <section class="schedule-section section-padding" id="section_4">
                <div class="container">
                    <div class="row">

                        <div class="col-12 text-center">
                            <h2 class="text-white mb-5">Match Schedule</h2>

                            <div class="table-responsive">
                                <table class="schedule-table table table-dark">
                                    <thead>
                                        <tr>
                                            <th scope="col">Date</th>

                                            <th scope="col">Saturday</th>

                                            <th scope="col">Sunday</th>

                                            <th scope="col">Monday</th>

                                        </tr>
                                    </thead>

                                    <tbody>
                                        <tr>
                                            <th scope="row">Day 1</th>

                                            <td class="table-background-image-wrap pop-background-image">
                                                <h3>Real Madrid</h3>
                                                <h3>VS Barcelona</h3>

                                                <p class="mb-2">8:00 PM</p>

                                                <p>Sentiago Bernabeu</p>

                                                <div class="section-overlay"></div>
                                            </td>

                                            <td style="background-color: #F3DCD4"></td>

                                            <td class="table-background-image-wrap rock-background-image">
                                                <h3>Liverpool</h3>
                                                <h3>VS Chelsea</h3>

                                                <p class="mb-2">11:00 PM</p>

                                                <p>Anfield</p>

                                                <div class="section-overlay"></div>
                                            </td>
                                        </tr>

                                        <tr>
                                            <th scope="row">Day 2</th>
                
                                            <td style="background-color: #ECC9C7"></td>

                                            <td>
                                                <h3>Studio Night</h3>

                                                <p class="mb-2">6:30 - 9:30 PM</p>

                                                <p>By Ryan Giggs</p>
                                            </td>

                                            <td style="background-color: #D9E3DA"></td>
                                        </tr>

                                        <tr>
                                            <th scope="row">Day 3</th>
                
                                            <td class="table-background-image-wrap country-background-image">

                                                <h3>Man united</h3>
                                                <h3>VS Man City</h3>
                                                <p class="mb-2">4:30 PM</p>
                                                <p>Old Trafford</p>


                                                <div class="section-overlay"></div>
                                            </td>

                                            <td style="background-color: #D1CFC0"></td>

                                            <td>
                                                <h3>Zamalek</h3>
                                                <h3>VS Ahly</h3>
                                                <p class="mb-2">10:00 PM</p>
                                                <p>Cairo</p>

                                            </td>
                                        </tr>
                                    </tbody>
                                </table>
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

.section-overlay {
  background-color: #000;
  position: absolute;
  top: 0;
  left: 0;
  pointer-events: none;
  width: 100%;
  height: 100%;
  opacity: 0.35;
}

.section-overlay + .container {
  position: relative;
}




.schedule-section {
  background-image: url('./images/nainoa-shizuru-unsplash-blur.jpg');
  background-color: #242424;
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

h2{
    font-size: 52px;
    font-weight: 700;
}
.table-responsive {
	filter: drop-shadow(2px 2px 4px #606060);
}

.schedule-table {
  border-radius: 20px;
  position: relative;
  overflow: hidden;
}

.schedule-table .bg-warning {
  background: #f0a5a5 !important;
}

.schedule-table thead th {
  background-color:#EE5007;
}

.schedule-table th,
.schedule-table tr,
.schedule-table td {
  border-bottom-color: #363a3e;
  padding: 30px;
}

.schedule-table tr:last-child th,
.schedule-table tr:last-child td {
  border-bottom-color: transparent;
}

.schedule-table thead th {
  border-right: 1px solid #c7460a;
  border-bottom-color: transparent;
}

.schedule-table th + td {
  border-bottom: 0;
}

.schedule-table thead th:last-child {
  border-right-color: transparent;
}

.schedule-table .pop-background-image {
  background-image: url('./images/clas.jpeg');
}

.schedule-table .rock-background-image {
  background-image: url('./images/salah.cms');
}

.schedule-table .country-background-image {
  background-image: url('./images/hall.jpeg');
}

.table-background-image-wrap {
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  box-shadow: none;
  position: relative;
}

.schedule-table h3,
.schedule-table p {
  color: #fff;
  position: relative;
  z-index: 2;
}


@media screen and (max-width: 991px) {
    h1 {
      font-size: 62px;
    }
  
    h2 {
      font-size: 36px;
    }
  
    h3 {
      font-size: 32px;
    }
  
    h4 {
      font-size: 28px;
    }
  
    h5 {
      font-size: 20px;
    }
  
    h6 {
      font-size: 18px;
    }
  
    .section-padding {
      padding-top: 50px;
      padding-bottom: 50px;
    }
    
  
    .schedule-table h3 {
      font-size: 22px;
    }
  
    .schedule-table th {
      padding: 20px;
    }
  
    .schedule-table tr, 
    .schedule-table td {
      padding: 25px;
    }
  
  }
  

  
  @media screen and (max-width: 480px) {
    h1 {
      font-size: 52px;
    }
  
    h2 {
      font-size: 28px;
    }
  
    h3 {
      font-size: 26px;
    }
  
    h4 {
      font-size: 22px;
    }
  
    h5 {
      font-size: 20px;
    }
  }


</style>
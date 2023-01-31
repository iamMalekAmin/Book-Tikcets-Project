<template>
    
    <section class="player-section section-padding" id="section_3">
                <div class="container">
                    <div class="row justify-content-center">

                        <div class="col-12 text-center">
                            <h2 class="mb-5">Meet Your Fav Players</h2>
                        </div>

                        <div class="col-lg-5 col-12">
                            <div class="player-thumb">
                                <div class="player-image-wrap">
                                    <img id="frs-img" src="./images/ronaldo.webp" class="player-image img-fluid">
                                </div>

                                <div class="player-hover">
                                    <p>
                                        <strong>Name:</strong>
                                        Cristiano Ronaldo
                                    </p>

                                    <p>
                                        <strong>Country:</strong>
                                        Portugal
                                    </p>

                                    <p>
                                        <strong>Age:</strong>
                                        37
                                    </p>

                                    <hr>

                                    <p class="mb-0">
                                        <strong>Instagram Account:</strong>
                                        <a href="https://www.instagram.com/cristiano/">Cristiano</a>
                                    </p>
                                </div>
                            </div>
                        </div>

                        <div class="col-lg-5 col-12">
                            <div class="player-thumb">
                                <div class="player-image-wrap">
                                    <img src="./images/Messi.jpg" class="player-image img-fluid">
                                </div>

                                <div class="player-hover">
                                    <p>
                                        <strong>Name:</strong>
                                        Lionel Messi
                                    </p>

                                    <p>
                                        <strong>Country:</strong>
                                        Argentina
                                    </p>

                                    <p>
                                        <strong>Age:</strong>
                                        35
                                    </p>

                                    <hr>

                                    <p class="mb-0">
                                        <strong>Instagram Account:</strong>
                                        <a href="https://www.instagram.com/leomessi/">leomessi</a>
                                    </p>
                                </div>
                            </div>

                            <div class="player-thumb">
                                <img src="./images/salah.cms" class="player-image img-fluid">

                                <div class="player-hover">
                                    <p>
                                        <strong>Name:</strong>
                                        Mohamed Salah
                                    </p>

                                    <p>
                                        <strong>Country:</strong>
                                        Egypt
                                    </p>

                                    <p>
                                        <strong>Age:</strong>
                                        31
                                    </p>

                                    <hr>

                                    <p class="mb-0">
                                        <strong>Instagram Account:</strong>
                                        <a href="https://www.instagram.com/mosalah/">mosalah</a>
                                    </p>
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



h2{
    font-size: 52px;
    font-weight: 700;
}

.player-thumb {
  position: relative;
  overflow: hidden;
  margin-bottom: 30px;
}

.player-image {
  border-radius: 20px;
  display: block;
  width: 100%;
}

#frs-img{
    height: 720px;
}

.player-thumb:hover .player-hover {
  transform: translateY(0);
  opacity: 1;
}

.player-hover {
  background-color: #F8CB2E;
  background-color: rgba(248, 203, 46, 0.75);
  border-radius: 20px;
  backdrop-filter: blur(5px) saturate(180%);
  -webkit-backdrop-filter: blur(5px) saturate(180%);
  margin: 20px;
  padding: 35px;
  transition: all 0.5s ease;
  transform: translateY(100%);
  position: absolute;
  bottom: 0;
  right: 0;
  left: 0;
  opacity: 0;
}

.player-hover p strong {
  color:  #ffffff;
  display: inline-block;
  min-width: 180px;
  margin-right: 20px;
}

.player-hover p a {
  color:  #EE5007;
}

.player-hover p a:hover {
  color: #ffffff;
}

.player-hover hr {
  margin: 1.5rem 0;
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
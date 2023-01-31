<script>
import { Icon } from "@iconify/vue";
</script>
<template>
  <section class="hero-section" id="section_1">
    <div class="section-overlay"></div>

    <div class="container d-flex justify-content-center align-items-center">
      <div class="row">
        <div class="col-12 mt-auto mb-5 text-center">
          <small>MA Live Presents</small>

          <h1 class="text-white mb-5">Match Live 2023</h1>
          <button class="btn" id="begin">Let's Begin</button>
        </div>
        <div
          class="
            col-lg-12 col-12
            mt-auto
            d-flex
            flex-column flex-lg-row
            text-center
          "
        >
          <div class="date-wrap">
            <h5 class="text-white">10 - 12<sup>th</sup>, Dec 2023</h5>
            <h5 class="text-white">Signal Iduna Park, Germany</h5>
          </div>
        </div>
      </div>
    </div>
    <div class="video-wrap">
      <video autoplay loop muted class="custom-video" poster="">
        <source src="../bg.mp4" type="video/mp4" />

        Your browser does not support the video tag.
      </video>
    </div>
  </section>
</template>

<style scoped>

#section_1{
  position: relative;
  width: 100%;
  height: 100vh;
}
* {
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

h1 {
  font-weight: 800;
  font-size: 5.2rem;
}

.section-overlay {
  background-color: #000000;
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

button {
  width: 120px;
  background-color: #ee5007;
  color: white;
  border-radius: 25px;
  font-weight: 700;
}
button:hover {
  background-color: #c01f27;
  color: white;
}

#begin {
  padding: 10px;
  font-size: 30px;
  font-weight: bold;
  width: 260px;
}

.hero-section {
  position: relative;
  overflow: hidden;
  padding-top: 100px;
  height: calc(100vh - 51px);
}

.hero-section small {
  color: white;
  text-transform: uppercase;
}

.hero-section .section-overlay {
  z-index: 2;
  opacity: 0.45;
}

.hero-section .container {
  position: relative;
  z-index: 2;
  height: 100%;
  padding-bottom: 50px;
}

.hero-section .container .row {
  height: 100%;
}

.video-wrap {
  z-index: -100;
}

.custom-video {
  position: absolute;
  top: 0;
  left: 0;
  object-fit: cover;
  width: 100%;
  height: 100%;
}
</style>
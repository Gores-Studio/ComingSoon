<template>
  <div class="row main-content">
    <div class="col-sm-12 col-md-6 h-100">
      <div class="d-flex flex-column align-items-center justify-content-center align-content-center h-100">
        <div class="logo text-center">
          <img src="/gores-logo.png" alt="Gores Digital" />
        </div>
        <div class="description text-center" style="margin-top: 70px">
          <span class="m-0 p-0" style="font-size: 48px"><strong>COMING SOON</strong></span>
        </div>
        <div class="text-center mt-3">
          <div class="text-center solution-print">
            <span style="font-size: 30px">Solusi Cetak <strong>Cepat</strong> dan <strong>Mudah</strong></span>
          </div>
        </div>
        <div style="padding-left: 50px; padding-right: 50px;">
          <p class="text-center mt-5" style="font-size: 20px">
            Cetak dan desain kebutuhan kamu di sini, dari mana saja dan kapan saja. Nikmati pengalaman dan kemudahan  dengan Gores Digital.
            Kami akan segera hadir!
          </p>
        </div>
        <div class="text-center">
          <p style="font-size: 15px; color: #4F4F4F">goresdigital</p>
        </div>
      </div>
      <div class="text-center support">
        <p style="font-size: 15px;">Supported : PT. Widya Dharma Shanti Denpasar | Gores Studio Bali</p>
      </div>
    </div>
    <div class="col-sm-12 col-md-6 h-100 d-none d-md-block" style="background-color: #C62D2D; color: #FFF">
      <div class="d-flex justify-content-end call-text">
        <p class="float-right text-right" style="font-size: 38px;  color: #FFF">
          <strong>Temukan</strong> <br/>
          berbagai kebutuhan <br/>
          cetakmu <strong>di sini!</strong>
        </p>
      </div>
      <div class="background-graphic">
        <img class="background-graphic" src="/image2.svg" />
        <img class="background-graphic" src="/image.svg" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>

<style>
html, body, #__nuxt, #__layout {
  height: 100%;
  width: 100%;
}

.solution-print {
  display: inline-block;
  background: rgb(198, 45, 45);
  color: #FFF;
  padding: 10px;
  padding-left: 30px;
  border-radius: 50px;
  padding-right: 30px;
}

.background-graphic {
  display: none;
  position: absolute;
  bottom: 0;
  right: 0;
}

.call-text {
  align-content: center;
  height: 100%;
  align-items: center;
}

@media (min-width: 1200px) {
  .background-graphic {
    display: block;
  }

  .call-text {
    height: auto;
    align-content: normal;
    align-items: start;
  }
}

.support {
  position: relative;
  bottom: auto;
  right: auto;
  left: auto;
}

.main-content {
  margin: auto;
  padding: 15px;
  height: auto;
}

@media (min-width: 380px) {
  .support {
    position: absolute;
    bottom: 0;
    right: 0;
    left: 0;
  }

  .main-content {
    margin: 0 !important;
    padding: 0;
    height: 100% !important;
  }
}

</style>

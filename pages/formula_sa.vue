<template>
  <div>
    <Header />
    <div class="container text-white">
      <Header-mobile />
      <b-row>
        <b-col cols="6" xl="3" class="mt-4">
          <NuxtLink to="/">
            <b-card class="card-dark" body-class="p-0" id="casino">
              <div class="text-area-ch2">
                <p class="mb-1">SA GAMING</p>
                <p class="mb-1"> <span class="text-brown">E01 </span> Room</p>
              </div>
              <div class="area-bar">
                <b-progress class="mt-2" :max="max" show-value>
                  <b-progress-bar :value="16" variant="success"></b-progress-bar>
                  <b-progress-bar :value="15" variant="danger"></b-progress-bar>
                </b-progress>
                <p class="text-center mt-1 mb-0"><span class="text-brown">Win Rate</span> : 43</p>
              </div>
              <b-button variant="play" class="py-1 mt-3">Play</b-button>
              <b-img src="~/assets/image/character/ch9.png" class="img-ch-9"></b-img>
              <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch2"></b-img>
            </b-card>
          </NuxtLink>
        </b-col>
        <b-col cols="6" xl="3" class="mt-4">
          <NuxtLink to="/">
            <b-card class="card-dark" body-class="p-0" id="casino">
              <div class="text-area-ch2">
                <p class="mb-1">SA GAMING</p>
                <p class="mb-1"> <span class="text-brown">E01 </span> Room</p>
              </div>
              <div class="area-bar">
                <b-progress class="mt-2" :max="max" show-value>
                  <b-progress-bar :value="16" variant="success"></b-progress-bar>
                  <b-progress-bar :value="15" variant="danger"></b-progress-bar>
                </b-progress>
                <p class="text-center mt-1 mb-0"><span class="text-brown">Win Rate</span> : 43</p>
              </div>
              <b-button variant="play" class="py-1 mt-3">Play</b-button>
              <b-img src="~/assets/image/character/ch10.png" class="img-ch-10"></b-img>
              <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch2"></b-img>
            </b-card>
          </NuxtLink>
        </b-col>
        <b-col cols="6" xl="3" class="mt-4">
          <NuxtLink to="/">
            <b-card class="card-dark" body-class="p-0" id="casino">
              <div class="text-area-ch2">
                <p class="mb-1">SA GAMING</p>
                <p class="mb-1"> <span class="text-brown">E01 </span> Room</p>
              </div>
              <div class="area-bar">
                <b-progress class="mt-2" :max="max" show-value>
                  <b-progress-bar :value="16" variant="success"></b-progress-bar>
                  <b-progress-bar :value="15" variant="danger"></b-progress-bar>
                </b-progress>
                <p class="text-center mt-1 mb-0"><span class="text-brown">Win Rate</span> : 43</p>
              </div>
              <b-button variant="play" class="py-1 mt-3">Play</b-button>
              <b-img src="~/assets/image/character/ch11.png" class="img-ch-9"></b-img>
              <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch2"></b-img>
            </b-card>
          </NuxtLink>
        </b-col>
        <b-col cols="6" xl="3" class="mt-4">
          <NuxtLink to="/">
            <b-card class="card-dark" body-class="p-0" id="casino">
             <div class="text-area-ch2">
                <p class="mb-1">SA GAMING</p>
                <p class="mb-1"> <span class="text-brown">E01 </span> Room</p>
              </div>
              <div class="area-bar">
                <b-progress class="mt-2" :max="max" show-value>
                  <b-progress-bar :value="16" variant="success"></b-progress-bar>
                  <b-progress-bar :value="15" variant="danger"></b-progress-bar>
                </b-progress>
                <p class="text-center mt-1 mb-0"><span class="text-brown">Win Rate</span> : 43</p>
              </div>
              <b-button variant="play" class="py-1 mt-3">Play</b-button>
              <b-img src="~/assets/image/character/ch12.png" class="img-ch-10"></b-img>
              <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch2"></b-img>
            </b-card>
          </NuxtLink>
        </b-col>
      </b-row>
    </div>
  </div>

</template>

<script>
  import Header from '~/components/header.vue'
  import Header_mobile from '~/components/header-mobile.vue'
  export default {
    data() {
      return {
        selected: null,
        value: 45,
        max: 31
      }
    },
    methods: {
      randomValue() {
        this.value = Math.random() * this.max
      }
    }
  }

</script>

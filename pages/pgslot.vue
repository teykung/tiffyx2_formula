<template>
  <div>
    <Header/>
    <div class="container text-white">
    <Header-mobile />
         <b-row>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game1.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Dimsummania</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game2.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Bikini Paradise</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game3.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Caishen Win</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
            <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game4.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Candy Burst</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game5.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Circus Delight</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game6.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Book Mystery</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game7.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Genesha Gold</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-slot text-center" body-class="p-0 pt-3">
               <b-img src="~/assets/image/pgslot/game8.png" class="mx-auto d-block" ></b-img>
               <p class="my-0">Genie's Wishes</p>
               <p class="my-0">อัตราชนะ</p>
               <p class="text-brown">80%</p>
               <div class="px-4">
               <b-progress :value="value" :max="max" show-value class="mb-3" variant="success"></b-progress>
                 </div>
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
        value: 80.333333333,
        max: 100
      }
    }
  }

</script>


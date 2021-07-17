<template>
  <div>
    <Header/>
    <div class="container text-white">
    <Header-mobile />
         <b-row>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/formula_sa">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">SA</h5>
                 <h5 class="text-white">GAMING</h5>
               </div>
               <b-img src="~/assets/image/character/ch1.png" class="img-ch-1"></b-img>
               <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">SEXY</h5>
                 <h5 class="text-white">GAMING</h5>
               </div>
               <b-img src="~/assets/image/character/ch2.png" class="img-ch-2"></b-img>
               <b-img src="~/assets/image/logo-game/sexy.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">WM</h5>
                 <h5 class="text-white">CASINO</h5>
               </div>
               <b-img src="~/assets/image/character/ch3.png" class="img-ch-3"></b-img>
               <b-img src="~/assets/image/logo-game/wm.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">DREAM</h5>
                 <h5 class="text-white">GAMING</h5>
               </div>
               <b-img src="~/assets/image/character/ch4.png" class="img-ch-4"></b-img>
               <b-img src="~/assets/image/logo-game/dream.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">CASINO</h5>
                 <h5 class="text-white">855</h5>
               </div>
               <b-img src="~/assets/image/character/ch5.png" class="img-ch-5"></b-img>
               <b-img src="~/assets/image/logo-game/855.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">HB</h5>
                 <h5 class="text-white">CASINO</h5>
               </div>
               <b-img src="~/assets/image/character/ch6.png" class="img-ch-5"></b-img>
               <b-img src="~/assets/image/logo-game/hb.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">ALLBET</h5>
               </div>
               <b-img src="~/assets/image/character/ch7.png" class="img-ch-5"></b-img>
               <b-img src="~/assets/image/logo-game/allbet.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">GCLUB</h5>
               </div>
               <b-img src="~/assets/image/character/ch8.png" class="img-ch-5"></b-img>
               <b-img src="~/assets/image/logo-game/gclub.png" class="logo-ch"></b-img>
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
      }
    }
  }

</script>

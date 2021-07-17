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
               <b-img src="~/assets/image/avatar/avt1.png" class="img-avt-1"></b-img>
               <b-img src="~/assets/image/logo-game/sa.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">JOKER</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt2.png" class="img-avt-2"></b-img>
               <b-img src="~/assets/image/logo-game/sexy.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">SEXY <br>GAME</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt3.png" class="img-avt-3"></b-img>
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
               <b-img src="~/assets/image/avatar/avt4.png" class="img-avt-4"></b-img>
               <b-img src="~/assets/image/logo-game/dream.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">PG</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt5.png" class="img-avt-5"></b-img>
               <b-img src="~/assets/image/logo-game/855.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">UFA</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt6.png" class="img-avt-6"></b-img>
               <b-img src="~/assets/image/logo-game/hb.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">SPADE</h5>
                 <h5 class="text-white">GAMING</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt7.png" class="img-avt-7"></b-img>
               <b-img src="~/assets/image/logo-game/allbet.png" class="logo-ch"></b-img>
             </b-card>
             </NuxtLink>
           </b-col>
           <b-col cols="6" xl="3" class="mt-4">
             <NuxtLink to="/">
             <b-card class="card-dark" body-class="p-0" id="casino">
               <div class="text-area-ch">
                 <p class="mb-1">BACCARAT</p>
                 <h5 class="text-white">RED</h5>
                 <h5 class="text-white">TIGER</h5>
               </div>
               <b-img src="~/assets/image/avatar/avt8.png" class="img-avt-8"></b-img>
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

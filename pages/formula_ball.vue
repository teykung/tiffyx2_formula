<template>
  <div>
    <Header/>
    <div class="container text-white" id="league">
      <Header-mobile />
          
      <h5>เลือกลีค</h5>
      <b-row>
        <b-col cols="12" xl="6">
          <b-form-select v-model="selected" class="mb-3">
            <b-form-select-option :value="null">
              <b-img src="~/assets/image/icon-eng.png" /> พรีเมียร์ลีก อังกฤษ - England
            </b-form-select-option>
          </b-form-select>
        </b-col>
        
      </b-row>
      <hr class="custom-line">
      <b-row>
        <b-col cols="6" xl="4">
          <b-card class="card-main">
            <b-img src="~/assets/image/lester.png" class="icon-country mx-auto d-block" />
            <label for="">ทีมเจ้าบ้าน</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                <b-img src="~/assets/image/icon-eng.png" /> เลสเตอร์ซิตี้ - Leicester
              </b-form-select-option>
            </b-form-select>
            <label for="">ลำดับ</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                ไม่มี
              </b-form-select-option>
            </b-form-select>
            <label for="">คะแนน</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                เลือก
              </b-form-select-option>
            </b-form-select>
            <b-form-group label="สภาพทีม" v-slot="{ ariaDescribedby }">
              <b-form-radio-group id="radio-slots" v-model="selectedx" :options="options"
                :aria-describedby="ariaDescribedby" name="radio-options-slots">
                <b-form-radio :value="{ one: 1 }">เต็มทีม</b-form-radio>
                <b-form-radio :value="{ two: 2 }">ไม่เต็มทีม</b-form-radio>
                <b-form-radio :value="{ three: 3 }">สำรอง</b-form-radio>
              </b-form-radio-group>
            </b-form-group>
          </b-card>
        </b-col>
        <b-col cols="6" xl="4" class="mt-4 mt-xl-0 mt-md-0">
          <b-card class="card-main">
            <b-img src="~/assets/image/evertan.png" class="mx-auto d-block icon-country" />
            <label for="">ทีมเจ้าบ้าน</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                <b-img src="~/assets/image/icon-eng.png" /> เอฟเวอร์ตัน - Evertan
              </b-form-select-option>
            </b-form-select>
            <label for="">ลำดับ</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                ไม่มี
              </b-form-select-option>
            </b-form-select>
            <label for="">คะแนน</label>
            <b-form-select v-model="selected" class="mb-3">
              <b-form-select-option :value="null">
                เลือก
              </b-form-select-option>
            </b-form-select>
            <b-form-group label="สภาพทีม" v-slot="{ ariaDescribedby }">
              <b-form-radio-group id="radio-slots" v-model="selectedx" :options="options"
                :aria-describedby="ariaDescribedby" name="radio-options-slots">
                <b-form-radio :value="{ four: 4 }">เต็มทีม</b-form-radio>
                <b-form-radio :value="{ five: 5 }">ไม่เต็มทีม</b-form-radio>
                <b-form-radio :value="{ six: 6 }">สำรอง</b-form-radio>
              </b-form-radio-group>
            </b-form-group>
          </b-card>
        </b-col>
        <b-col cols="12" xl="4" class="mt-xl-4 mt-4">
          <b-card class="football-result text-white">
            <h5 class="text-white mb-3">ผลคำนวนที่คาด</h5>
            <table class="table text-white">
              <thead>
                <tr>
                  <th scope="col" class="text-left">เจ้าบ้าน</th>
                  <th scope="col" class="text-center">สกอร์/สูงต่ำ</th>
                  <th scope="col" class="text-right">เยือน</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
                <tr>
                  <td class="text-left"> <img src="~/assets/image/lester.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เลสเตอร์ซิตี้</td>
                  <td class="text-center">3-0</td>
                  <td class="text-right"> <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country">&nbsp;&nbsp;เอฟเวอร์ตัน</td>
                </tr>
              </tbody>
            </table>
          </b-card>
        </b-col>
        <b-col cols="12" xl="12" class="mt-4" id="league-select">
          <b-card class="card-main p-0" body-class="p-0">
            <h5 class="px-4 py-2 mb-1">คู่แข่งขัน</h5>
            <div class="bg-brown text-white px-4">League</div>
            <div class="p-4">
              <div class="form-check form-check-inline">
              <b-row>
                <b-col cols="12" xl="5">
                  <hr class="custom-line d-block d-xl-none d-md-none">
                      <b-row>
                        <b-col cols="12" xl="4" class="mb-2">
                           <img src="~/assets/image/lester.png" alt=""
                      class="icon-country"> &nbsp;เลสเตอร์ซิตี้
                        </b-col>
                        <b-col cols="6" xl="3">
                           <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="dsadsadsa">
                           <label class="form-check-label" for="inlineRadio1">ทีมต่อ</label>
                        </b-col>
                        <b-col cols="6" xl="3">
                           <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="dsadasd">
                           <label class="form-check-label" for="inlineRadio1">ทีมรอง</label>
                        </b-col>
                      </b-row>
                </b-col>
                <b-col cols="12" xl="2" class="d-none d-xl-block d-md-block">
                  VS
                </b-col>
                <b-col cols="12" xl="5">
                  <hr class="custom-line d-block d-xl-none d-md-none">
                      <b-row>
                        <b-col cols="12" xl="4" class="mb-2">
                           <img src="~/assets/image/evertan.png" alt=""
                      class="icon-country"> &nbsp;เอฟเวอร์ตัน
                        </b-col>
                        <b-col cols="6" xl="3">
                           <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="dsadsadsa">
                           <label class="form-check-label" for="inlineRadio1">ทีมต่อ</label>
                        </b-col>
                        <b-col cols="6" xl="3">
                           <input class="form-check-input" type="radio" name="inlineRadioOptions" id="inlineRadio1" value="dsadasd">
                           <label class="form-check-label" for="inlineRadio1">ทีมรอง</label>
                        </b-col>
                      </b-row>
                </b-col>
              </b-row>
              </div>
              </div>
          </b-card>
        </b-col>
      </b-row>
    </div>
  </div>

</template>

<script>
import Header from '~/components/header.vue'
  export default {
    data() {
      return {
        selected: null,
      }
    }
  }

</script>

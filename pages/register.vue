<template>
  <div>
    <b-jumbotron class="header">
      <div class="container">
        <div class="ponypink-object">
          <b-row>
            <b-col cols="12" xl="5" class="mr-xl-auto text-center text-xl-left d-none d-xl-block d-md-block">
              <h1>PONY PINK</h1>
              <h2 class="ml-xl-4 ml-0">C A S I N O &nbsp;&nbsp; H A C K</h2>
              <b-button variant="circle" class="mt-4 d-none d-xl-block d-md-block">
                <span class="bg-circle">LOGIN</span>
              </b-button>
              <b-button variant="circle-sm" class="mt-4 d-block d-xl-none d-md-none">
                <span class="bg-circle">LOGIN</span>
              </b-button>
            </b-col>
            <b-col cols="12" xl="1">

            </b-col>
            <b-col cols="12" xl="6" class="auth-section">
              <b-card-text class="pt-0">
                <b-button variant="login-active" to="/login">เข้าสู่ระบบ</b-button>
                <b-button variant="login" to="/register">สมัครสมาชิก</b-button>
                <h5 class="mt-3">สร้างบัญชีของฉัน</h5>
                <b-row>
                  <b-col cols="12" xl="6">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">ชื่อ - สกุล</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                  <b-col cols="12" xl="6">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">เบอร์โทรศัพท์ 10 หลัก</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                  <b-col cols="12" xl="6" class="mt-xl-3">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">สร้างรหัสผ่าน</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                  <b-col cols="12" xl="6" class="mt-xl-3">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">ยืนยันรหัสผ่าน</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                </b-row>
                <hr>
                <h5 class="mt-2">บัญชีรับเงินของคุณ</h5>
                <b-row>
                  <b-col cols="12" xl="6">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">เลือกธนาคาร</p>
                <b-select>
                  <option value="1" active>ธนาคารกสิกรไทย</option>
                </b-select>
                  </b-col>
                  <b-col cols="12" xl="6">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">เลขบัญชี</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                  <b-col cols="12" xl="6" class="mt-xl-3">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">กรอกไอดีไลน์</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                  </b-col>
                  <b-col cols="12" xl="6" class="mt-xl-3">
                    <p class="mb-2 mb-xl-2 mt-2 mt-xl-0">คุณรู้จักเราจากช่องทางไหน</p>
                <b-select>
                  <option value="1" active>Facebook</option>
                </b-select>
                  </b-col>
                </b-row>
                <b-button variant="brown" block class="mt-4 col-12 col-xl-6">
                  <i class="mdi mdi-account-outline"></i> เข้าสู่ระบบ
                </b-button>
              </b-card-text>
            </b-col>
            
          </b-row>
          <img src="~/assets/image/D1.png" alt="" class="D1 img-fluid d-none d-xl-block d-md-none">
          <img src="~/assets/image/gem_01.png" alt="" class="gem-01 img-fluid d-none d-xl-block d-md-none">
          <img src="~/assets/image/gem_02.png" alt="" class="gem-02 img-fluid d-none d-xl-block d-md-none">
          <img src="~/assets/image/gem_04.png" alt="" class="gem-03 img-fluid d-none d-xl-block d-md-none">
          <img src="~/assets/image/gem_03.png" alt="" class="gem-04 img-fluid d-none d-xl-block d-md-none">
        </div>
        <img src="~/assets/image/avatar.png" alt="" class="avatar-large img-fluid d-none d-xl-none d-md-none">
      </div>
    </b-jumbotron>
    <div class="ci">
      <b-container>
        <b-row>
          <b-col cols="12" xl="8">
            <img src="~/assets/image/mega.png" alt="" class="mega-vdo mt-0 mt-xl-5 img-fluid">
            <img src="~/assets/image/play.png" alt="" class="play-vdo img-fluid">
          </b-col>
        </b-row>
        <img src="~/assets/image/avatar.png" alt="" class="avatar-large img-fluid d-xl-block d-md-none d-none">
      </b-container>

    </div>

  </div>

</template>

<script>
  export default {}

</script>

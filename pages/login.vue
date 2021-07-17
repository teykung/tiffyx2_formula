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
            <b-col cols="12" xl="3" class="auth-section">
              <b-card-text class="pt-0">
                <b-button variant="login" to="/login">เข้าสู่ระบบ</b-button>
                <b-button variant="login-active" to="/register">สมัครสมาชิก</b-button>
                <p class="mb-2 mt-4">เบอร์โทรศัพท์ 10 หลัก</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                <p class="my-2 mt-3">รหัสผ่าน</p>
                <b-input placeholder="โปรดระบุ"></b-input>
                <div class="text-right my-2 mb-3 aa">
                  <a href="#">ลืมรหัสผ่าน</a>
                </div>
                <b-button variant="brown" block>
                  <i class="mdi mdi-account-outline"></i> เข้าสู่ระบบ
                </b-button>
              </b-card-text>
            </b-col>
            <b-col cols="12" xl="2">

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

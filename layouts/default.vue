<template>
  <div>
    <b-navbar type="dark" variant="tran" class="fixed-top">
      <div class="container">
<b-navbar-nav class="ml-auto">
            <b-button variant="dark-pony" class="mx-2" to="/login">
              <i class="mdi mdi-account-outline icon-card"></i> เข้าสู่ระบบ
            </b-button>
            <b-button variant="brown" class="mr-3" to="/register"> <i class="mdi mdi-login icon-card"></i> สมัครสมาชิก</b-button>
            <b-dropdown variant="lang">
              <template #button-content>
                <i class="mdi mdi-earth"></i>
              </template>
              <b-dropdown-item href="#">An item</b-dropdown-item>
              <b-dropdown-item href="#">Another item</b-dropdown-item>
            </b-dropdown>
          </b-navbar-nav>
      </div>
    </b-navbar>
    <Nuxt />
    <footer class="mt-5"></footer>
  </div>
</template>

<script>
  export default {

  }

</script>

<template>
  <div>
      <navbar-component></navbar-component>
      <sidebar-component></sidebar-component>
      <div class="content-wrapper">            
          <div class="content-header">
              <div class="container-fluid">
                  <div class="row mb-2">
                      <div class="col-sm-6">
                          <h1 class="m-0 font-weight-bold">Dashboard</h1>
                      </div>          
                  </div>
              </div>
          </div>

          <div class="content">
              <div class="container-fluid">
                  <div class="row">
                      <div class="col-lg-12">
                          <div class="card card-primary card-outline">
                              <div class="card-body">
                                  <h5 class="card-title">Selamat Datang</h5>

                                  <p class="card-text">
                                      Website Perpustakaan Online Vue
                                  </p>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
      </div>        
  </div>
</template>

<script>
import AppNavbar from '../components/template/AppNavbar.vue'
import AppSidebar from '../components/template/AppSidebar.vue'
export default {
  components: {
        'navbar-component' : AppNavbar,
        'sidebar-component' : AppSidebar,
  }
}
</script>
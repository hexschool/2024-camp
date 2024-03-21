<template>
  <header>
    <nav class="navbar navbar-expand-md">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="@/assets/images/logo.png" alt="logo">
        </a>
        <button class="navbar-toggler border-0 shadow-none" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggler" aria-controls="navbarToggler" aria-expanded="false" aria-label="Toggle navigation">
          <span class="material-symbols-outlined fs-1">menu</span>
        </button>
        <div class="collapse navbar-collapse offset-md-3" id="navbarToggler">
          <ul class="navbar-nav me-auto mb-2 mb-md-0 text-center">
            <li class="nav-item mb-4 mb-md-0 me-md-3 me-lg-7">
              <a class="nav-link position-relative py-1 active" aria-current="page" href="#">首頁</a>
            </li>
            <li class="nav-item mb-4 mb-md-0 me-md-3 me-lg-7">
              <a class="nav-link position-relative py-1" href="#">作品集</a>
            </li>
            <li class="nav-item mb-4 mb-md-0 me-md-3 me-lg-7">
              <a class="nav-link position-relative py-1" href="#">服務項目</a>
            </li>
            <li class="nav-item mb-4 mb-md-0 me-md-3 me-lg-7">
              <a class="nav-link position-relative py-1" href="#">部落格</a>
            </li>
            <li class="nav-item">
              <a class="nav-link position-relative py-1" href="#">聯絡我</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
  import '/node_modules/bootstrap/js/index.esm.js';
</script>

<style lang="scss" scoped>

</style>
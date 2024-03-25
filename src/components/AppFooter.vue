<template>
  <footer
    class="py-7"
    style="background-image: url('/src/assets/images/footer-bg-lg.png');
      background-repeat: no-repeat;
      background-size: cover;"
  >
    <div class="container">
      <div class="row row-gap-7 justify-content-between align-items-center my-md-7">
        <div class="col-12 col-md-4 col-lg-3">
          <img
            class="mb-4"
            style="width: 120px;"
            src="@/assets/images/logo.svg" alt="logo"
          >
          <p class="mb-4 fs-5 text-primary-700">歡迎填寫表單，或直接與我聯絡！</p>
          <a
            class="link-primary-500 fs-5 text-decoration-none" href="mailto:service@hexschool.com">service@hexschool.com</a>
        </div>
        <div class="col-12 col-md-6 col-lg-4 col-xxl-3">
          <a class="btn btn-lg w-100 px-4 mb-4 lh-base text-start fw-bold text-primary-50 bg-primary-900" href="#">
            <img src="@/assets/images/list.svg" alt="list">
            填寫表單
          </a>
          <a class="btn btn-lg w-100 px-4 mb-4 lh-base text-start icon-hover link-primary-700 bg-primary-50" href="#">
            <i class="bi bi-instagram align-middle px-2 fs-1"></i>
            hexschool_demo
          </a>
          <a class="btn btn-lg w-100 px-4 lh-base text-start icon-hover link-primary-700 bg-primary-50" href="#">
            <i class="bi bi-facebook align-middle px-2 fs-1"></i>
            hexschoolTW
          </a>
        </div>
      </div>
    </div>
  </footer>
</template>
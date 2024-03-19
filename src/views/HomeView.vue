<script setup>
import AppHeader from '@/components/AppHeader.vue';
</script>

<template>
  <AppHeader />
  <main>
    <div class="container-fluid">
      <div class="row flex-md-row-reverse mb-7 mb-md-9">
        <div class="col-12 col-md-7 px-0 overflow-hidden">
          <picture>
            <source media="(min-width: 768px)" srcset="@/assets/images/hero-lg.png">
            <img class="w-100" src="@/assets/images/hero-sm.png" alt="hero banner">
          </picture>
        </div>
        <div class="col-10 col-md-4 mx-auto mx-md-0">
          <div class="d-flex flex-column justify-content-center align-items-center align-items-md-start h-100">
            <h1 class="mb-4 text-primary-700 fw-semibold">Hi！我是 Noel</h1>
            <p class="text-center text-md-start text-primary-600 fs-5 mb-0">具有 10 年經驗的<mark class="mark">資深 UI 設計師</mark>兼<mark class="mark">前端工程師</mark></p>
            <p class="text-center text-md-start text-primary-600 fs-5">技術雙修並行，熱衷於優化使用者的網頁體驗</p>
            <p class="text-center text-md-start text-primary-400 mb-9">WEB DEVELOPMENT / BRANDING / UI / UX / APP DESIGN</p>
            <div>
              <a class="px-2 pe-3" href="#">
                <img src="@/assets/images/instagram.svg" alt="instagram">
              </a>
              <a class="px-2" href="#">
                <img src="@/assets/images/facebook.svg" alt="facebook">
              </a>
              <a class="px-2" href="#">
                <img src="@/assets/images/youtube.svg" alt="youtube">
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <h2 class="title-deco py-7 py-md-9 text-center text-primary-700 tracking-wide fw-semibold">作品介紹</h2>
    <section
      class="pt-9"
      style="background-image: url('/src/assets/images/homepage-work1-bg.png');background-repeat: no-repeat;background-position: center;background-size: cover;"
    >
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-6">
            <img class="img-fluid" src="@/assets/images/homepage-work1.png" alt="work1">
          </div>
          <div class="col-12 col-md-6 d-none d-md-flex flex-md-column justify-content-center">
            <div class="px-7 py-9 bg-white-overlay rounded-5">
              <h3 class="mb-2 text-primary-50">星際旅行訂票平台</h3>
              <p class="mb-3 fs-6 text-primary-50">悠遊宇宙的夢想，從這裡開始實現</p>
              <div class="pb-7 mb-7 border-bottom border-white">
                <span class="badge me-2 fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">網頁設計</span>
                <span class="badge me-2 fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">響應式設計</span>
                <span class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">Bootstrap</span>
              </div>
              <div class="d-flex justify-content-center">
                <a
                  class="btn btn-lg px-6 py-3 fs-5 fw-bold text-primary-50 bg-primary-900"
                  href="#"
                >
                  完整介紹
                  <span class="material-symbols-outlined align-text-bottom">arrow_forward</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="d-md-none pt-4 pb-8 text-center">
      <h3 class="mb-2">星際旅行訂票平台</h3>
      <p class="mb-3 fs-6 text-primary-600">悠遊宇宙的夢想，從這裡開始實現</p>
      <div class="mb-4">
        <span class="badge me-2 fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">網頁設計</span>
        <span class="badge me-2 fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">響應式設計</span>
        <span class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">Bootstrap</span>
      </div>
      <a
        class="btn btn-sm px-3 py-2 fs-6 fw-bold text-primary-50 bg-primary-900"
        href="#"
      >
        完整介紹
        <span class="material-symbols-outlined align-top">arrow_forward</span>
      </a>
    </div>
  </main>

  
</template>

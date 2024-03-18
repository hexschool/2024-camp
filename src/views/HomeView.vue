<script setup>
import AppHeader from '@/components/AppHeader.vue';
</script>

<template>
  <AppHeader />
  <main class="container-fluid">
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
    <h2 class="title-deco py-7 py-md-9 text-center text-primary-700 tracking-wide fw-semibold">作品介紹</h2>
  </main>

  
</template>

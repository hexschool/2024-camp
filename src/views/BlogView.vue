<script setup>
  const importImage = (num) => {
    const image = new URL(`../assets/images/article-image${num}.png`, import.meta.url);
    return image.href;
  }
</script>

<template>
  <main>
    <section class="container pb-7 pb-md-9">
      <div class="py-7 py-md-9 mt-md-9">
        <h2 class="title-deco mb-3 mb-md-4 text-center text-primary-700 tracking-wide fw-semibold">部落格</h2>
        <p class="mb-0 text-center text-primary-500">不定期分享技術文章</p>
      </div>
      <div class="row flex-row-reverse">
        <div class="col-12 col-lg-3">
          <aside class="blog__menu px-3 py-4 p-lg-7 bg-primary-100">
            <ul class="d-flex flex-lg-column justify-content-md-center justify-content-lg-start gap-7 mb-0 p-xxl-7 list-unstyled">
              <li class="flex-shrink-0">
                <button class="blog__menu--active pb-1 text-primary-800 bg-transparent" type="button">全部文章</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 text-primary-800 bg-transparent border-0" type="button">UI/UX 新知</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 text-primary-800 bg-transparent border-0" type="button">數位產品設計</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 text-primary-800 bg-transparent border-0" type="button">平面設計</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 text-primary-800 bg-transparent border-0" type="button">前端開發</button>
              </li>
            </ul>
          </aside>
        </div>
        <ul class="d-flex flex-column row-gap-7 row-gap-lg-9 gx-9 gx-lg-4 col-12 col-lg-9 mt-9 mt-lg-0 mb-0 pt-9 pt-lg-0">
          <li
            v-for="(num, index) in 6"
            :key="index"
            class="card border-0 "
          >
            <div class="row g-0">
              <div class="col-12 col-lg-4">
                <img
                  :src="importImage(num)"
                  class="img-fluid w-100 h-100 object-fit-cover rounded-3"
                  alt="article-1"
                >
              </div>
              <div class="col-12 col-lg-8">
                <div class="card-body pt-lg-0 pe-lg-0">
                  <div class="d-flex justify-content-between align-items-center mb-3">
                    <p class="card-text mb-0 fs-6 text-primary-600">
                      <small class="text-body-secondary">2024/02/10</small>
                    </p>
                    <span class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">UI/UX 新知</span>
                  </div>
                  <h5 class="card-title mb-3 text-primary-700">Vision Pro 登場！Vision Pro UI/UX 設計重點大公開 (上)</h5>
                  <p class="mb-0 text-primary-700">Vision Pro 終於在 2024 年 2 月正式開賣，距離正式發表的 2023 年 6 月，已有半年時間。</p>
                  <p class="d-none d-lg-block mb-0 text-primary-700">這半年間，各種質疑聲不斷冒出，例如「太貴了，這是做給投資家看的產品，不能真的大量生產」、「續航力明顯不足，電池太重，不利於隨身攜帶使用」、「隔絕現實世界，會更加深世代或人際關係的隔閡」。</p>
                  <a class="stretched-link" href="#"></a>
                </div>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </section>
  </main>
</template>
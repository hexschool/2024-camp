<template>
  <main>
    <section class="pt-md-7 pb-7 pb-md-9">
      <div class="container">
        <h2 class="title-deco py-7 py-md-9 text-center text-primary-700 tracking-wide fw-semibold">服務項目</h2>
        <div class="row row-gap-4 mb-7 mb-md-9">
          <div class="col-11 col-md-6 col-lg-3 mx-auto">
            <div class="bg-service d-flex flex-column justify-content-center align-items-center rounded-4">
              <div class="position-absolute start-0 end-0 top-0 bottom-0 d-flex flex-column justify-content-center align-items-center">
                <img class="mb-4" src="@/assets/images/service-item-visual.png" alt="visual design">
                <h3 class="text-primary-50">平面設計</h3>
              </div>
            </div>
          </div>
          <div class="col-11 col-md-6 col-lg-3 mx-auto">
            <div class="bg-service d-flex flex-column justify-content-center align-items-center rounded-4">
              <div class="position-absolute start-0 end-0 top-0 bottom-0 d-flex flex-column justify-content-center align-items-center">
                <img class="mb-4" src="@/assets/images/service-item-ui.png" alt="ui design">
                <h3 class="text-primary-50">UI 設計</h3>
              </div>
            </div>
          </div>
          <div class="col-11 col-md-6 col-lg-3 mx-auto">
            <div class="bg-service d-flex flex-column justify-content-center align-items-center rounded-4">
              <div class="position-absolute start-0 end-0 top-0 bottom-0 d-flex flex-column justify-content-center align-items-center">
                <img class="mb-4" src="@/assets/images/service-item-html&css.png" alt="html and css">
                <h3 class="text-primary-50">切版服務</h3>
              </div>
            </div>
          </div>
          <div class="col-11 col-md-6 col-lg-3 mx-auto">
            <div class="bg-service d-flex flex-column justify-content-center align-items-center rounded-4">
              <div class="position-absolute start-0 end-0 top-0 bottom-0 d-flex flex-column justify-content-center align-items-center">
                <img class="mb-4" src="@/assets/images/service-item-front-end.png" alt="visual design">
                <h3 class="text-primary-50">前端開發</h3>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-service px-2 py-7 pb-md-9">
      <div class="container">
        <h2 class="title-deco py-7 py-md-9 text-center text-primary-50 tracking-wide fw-semibold">服務流程</h2>
        <div
          class="d-flex flex-column row-gap-3 mx-auto"
          style="max-width: 655px;"
        >
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">1</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">初步接洽</h3>
              <p class="mb-0 fs-5 text-primary-300">透過表單或其他社群軟體與我聯絡</p>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">根據難易度與複雜度，後續可能需要電話/線上討論</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">2</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">需求釐清</h3>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">透過訪談與問卷，解析客戶需求，並針對痛點給予實際建議</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">3</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">委託簽約</h3>
              <p class="mb-0 fs-5 text-primary-300">合約雙方用印後，即正式開始合作</p>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">可提供發票或勞務報酬單，須支付 20% 訂金</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">4</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">版本呈現</h3>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">根據合約內容進行設計或開發</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">5</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">來回修正</h3>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">依據合約規定之修正次數進行，次數計算以 mail 為準</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">6</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">終版確認</h3>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">雙方同意後即為最終版</p>
            </div>
          </div>
          <span class="material-symbols-outlined fs-2 text-center text-primary-600">arrow_downward</span>
          <div class="d-flex flex-column flex-md-row align-items-center px-4 px-md-6 py-4 mb-7 mb-md-9 bg-primary-700 border border-1 border-primary-500 rounded-1">
            <div class="font-tourney display-2 text-primary-500">7</div>
            <div class="ms-0 ms-md-6">
              <h3 class="text-center text-md-start text-primary-50">結案</h3>
              <p class="mb-4 mb-md-0 fs-5 text-primary-300">客戶簽署驗收單，並於約定日期支付尾款</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
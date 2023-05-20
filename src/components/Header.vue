<template>
  <header>
    <div class="collapse bg-dark" id="navbarHeader">
      <div class="container">
        <div class="row">
          <div class="col-sm-8 col-md-7 py-4">
            <h4 class="text-white">봉사 신청 사이트</h4>
            <p class="text-muted">회원님의 관심 분야 혹은 전공에 맞추어 IT 교육 봉사를 신청 가능하게 하여 봉사자와 학습자 모두 만족 가능한 사이트 입니다. </p>
          </div>
          <div class="col-sm-4 offset-md-1 py-4">
            <h4 class="text-white">메뉴</h4>
            <ul class="list-unstyled">
              <li><a href="#" class="text-white">내 정보</a></li>
              <li><a href="#" class="text-white">내 데이터</a></li>
              <li><a href="#" class="text-white">로그아웃</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container">
        <a href="#" class="navbar-brand d-flex align-items-center">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" aria-hidden="true" class="me-2" viewBox="0 0 24 24"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
          <strong>봉사 모집</strong>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarHeader" aria-controls="navbarHeader" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',


}
</script>

<style scoped>

</style>

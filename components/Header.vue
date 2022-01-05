<template>
  <header class="header">
    <div class="container">
      <div class="logo">
        <img src="/assets/img/logo_sticky.png" alt="" />
      </div>
      <nav>
        <ul class="nav-list">
          <li class="nav-item">
            <a href="">PIX TECHの特徴</a>
          </li>
          <li class="nav-item">
            <a href="">PIX TECHの思い</a>
          </li>
          <li class="nav-item">
            <a href="">カリキュラム</a>
          </li>
          <li class="nav-item">
            <a href="">コースの紹介</a>
          </li>
          <li class="nav-item">
            <a href="">講師の紹介</a>
          </li>
          <li class="nav-item">
            <a href="">よくある質問</a>
          </li>
          <li class="nav-item">
            <a href="">説明会へ申し込む</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use "@/assets/styles/global" as *;
.header {
  color: $font-black;
}
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.nav-list {
  display: flex;
  align-items: center;
  justify-content: center;
}
.nav-item {
  & + & {
    margin-left: 20px;
  }
}
</style>

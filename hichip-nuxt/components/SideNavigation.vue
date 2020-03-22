<template>
  <div
    class="ui vertical inverted menu"
    style="height: 100vh;width: 270px; background:white;border-right: solid 1px #f0f0f0;"
  >
    <div class="item" style="width: 100px;margin: auto;">
      <a class="ui logo icon image">
        <img src="https://hichip.sakura.ne.jp/img/logo.png" width="60px;" />
      </a>
    </div>

    <h1 style="margin: auto;margin-bottom: 30px;width: 104px;">G's Chip</h1>
    <div class="wrapper-points" style="padding-bottom:20px;border-bottom:solid 0.1px #f0f0f0;">
      <div class="itemv" style="display:flex; justify-content:space-around;">
        <div class>
          <h6 width="70px">今月もらった</h6>
          <!-- <div class="">  <span>ポイント</span> </div> -->
          <div>0ポイント</div>
          <div>(累計：150)</div>
        </div>
        <div class="current_available_point">
          <h6>今週使える</h6>
          <div class>
            8
            <span>ポイント</span>
          </div>
        </div>
      </div>
    </div>
    <a
      class="sidebar-item"
      style="display:block"
      href="/"
    >タイムライン</a>
    <a
      class="sidebar-item"
      style="display:block"
      href="/prologue"
    >マイページ</a>
    <a
      class="sidebar-item"
      style="display:block"
      href="/prologue"
    >プロローグ</a>
    <!-- <a class="sidebar-item" style="display:block" href=""> よくある質問</a>
                    <a class="sidebar-item" style="display:block" href=""> ダッシュボード</a>
    <a class="sidebar-item" style="display:block" href=""> プロローグ</a>-->
  </div>
</template>

<style>

</style>

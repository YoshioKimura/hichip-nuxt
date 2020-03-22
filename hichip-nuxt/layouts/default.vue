<template>

  <div class="container1">
    <div class="flex-wrapper" style="display:flex">
      <div class="toc">
        <SideNavigation />
      </div>
      <div class="test" style="width: 100%;">
        <div
          class="ui inverted large borderless fluid menu column h20"
          style="background-color:#ffffffe6;border-bottom: solid 1px #f0f0f0;min-height: 3.857143em;"
        >
          <div class="ui inverted buttoncolor button">
            <a href="https://hichip.sakura.ne.jp/userlist.php">チップをおくる</a>
          </div>
          <div class="right menu">
            <div class="ui dropdown item">
              <div class="header">
                <h4>MENU</h4>
              </div>
              <i class="share square icon"></i>
              <div class="menu">
                <div class="item">
                  <small>
                    <i class="reply icon"></i>
                    <a class="dropdown-item" href="https://hichip.sakura.ne.jp/userlist.php">チップをおくる</a>
                  </small>
                </div>
                <div class="item">
                  <small>
                    <i class="clipboard outline icon"></i>
                    <a class="dropdown-item" href="https://hichip.sakura.ne.jp/logout.php">ログアウト</a>
                  </small>
                </div>
              </div>
            </div>
          </div>
        </div>
          <nuxt />
      </div>
    </div>
  </div>
</template>

<script>
import SideNavigation from "@/components/SideNavigation";

export default {
  components: {
    SideNavigation
  }
};
</script>

<style>
/* html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
} */




</style>

<template>
  <div class="container1">
        <action />
        <timeline />
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import Action from "~/components/Action.vue";
import Timeline from "~/components/Timeline.vue";

export default {
  components: {
    Logo,
    Action,
    Timeline
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.btn-good {
  display: inline-block;
  padding: 0 8px;
  cursor: pointer;
}

.btn-good:hover {
  color: #f44336;
}

.active {
  color: #f44336;
}

.btn-good .active {
  color: #f44336;
}

body {
  font-family: "font name", sans-serif;
}

.event {
  padding-top: 30px !important;
  padding-bottom: 30px !important;
  border-top: solid 1px #f0f0f0 !important;
}

.inverted .header,
.inverted .item {
  color: #000000de !important;
  padding-left: 20px !important;
}

.sidebar-item {
  color: #000000de;
  font-size: 1em;
  font-weight: bold;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 40px;
  transition: background-color 0.1s linear;
}

.sidebar-item:hover {
  color: #000000de;
  font-size: 1em;
  font-weight: bold;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 40px;
  background: #f2f2f2;
}

* {
  margin: 0;
  padding: 0;
}

.ui.large.menu {
  margin-top: 0;
}

.test {
  overflow-x: hidden;
}

.h20 div {
  /* padding:1em; */
}

.buttoncolor {
  background-color: #0000;
  color: #e684c3 !important;
  border: solid #e684c3 1px !important;
  border-radius: 25px !important;
  height: 40px !important;
  margin-top: 10px !important;
  position: absolute !important;
  right: 150px !important;
  width: 145px;
}

.buttoncolor a {
  text-decoration: none !important;
  color: #e684c3 !important;
  display: block !important;
}

.buttoncolor a:hover {
  text-decoration: none !important;
  color: #fff !important;
  display: block !important;
}

.buttoncolor:hover {
  background-color: #e684c3 !important;
  color: #fff !important;
  border: solid #e684c3 1px !important;
  background-clip: padding-box;
  border-radius: 25px !important;
  height: 100%;
  margin-top: 10px !important;
  position: absolute !important;
  right: 150px !important;
}

.buttoncolor:hover > a {
  text-decoration: none !important;
  color: #fff !important;
  display: block;
}

small a.dropdown-item {
  color: #000000de;
}
</style>

<template>
  <div id="app">
    <div class="header">
      <div class="header-img"></div>
    </div>
    <header>
      <h1>
        El
        <span>Tiempo</span>
      </h1>
    </header>
    <div class="container">
      <br />
      <router-view />
    </div>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>
<style>
@font-face {
  font-family: "Sucrose Bold Two";
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/sucrose.woff2")
    format("woff2");
}
@font-face {
  font-family: "IM Fell French Canon Pro";
  src: url("https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/im-fell-french-canon-pro.woff2")
    format("woff2");
}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
}
header {
  background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/mountain-range.jpg)
    no-repeat;
  padding-top: 33%;
  background-size: 100%;
  font-family: "Sucrose Bold Two";
}
header img {
  position: absolute;
  top: 0;
  right: 0;
  width: 45.8%;
}
header h1 {
  position: absolute;
  top: 2rem;
  right: 2rem;
  font-size: 12vw;
  line-height: 0.8;
  margin-top: 0;
  text-align: center;
}
header h1 span {
  display: block;
  font-size: 8.75vw;
}
main {
  background: #fff;
  position: relative;
  border: 1px solid #fff;
  font-family: "IM Fell French Canon Pro";
  font-size: 1.4rem;
  padding: 2rem 25%;
  line-height: 1.6;
}
@media all and (max-width: 400px) {
  main {
    padding: 2rem;
  }
}
</style>

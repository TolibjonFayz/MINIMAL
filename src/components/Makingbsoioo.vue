<template>
  <div class="making">
    <h1 class="making-main">Making brands stand out is our obsession</h1>
    <div class="line"></div>
    <h2 class="making-h2">Let us help your brand stand out.</h2>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.making {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 280px;
  background-image: url("../making.png");
  background-size: cover;
  .making-main {
    width: 60%;
    color: #fff;
    text-align: center;
    font-family: Montserrat;
    font-size: 44px;
    font-style: normal;
    font-weight: 300;
    line-height: 55px;
    text-transform: uppercase;
  }
  .line {
    width: 80px;
    height: 2px;
    background: #fff;
    text-align: center;
  }
  .making-h2 {
    color: rgba(255, 255, 255, 0.81);
    text-align: center;
    font-family: Vollkorn;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
  }
}
</style>

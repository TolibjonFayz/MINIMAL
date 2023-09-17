<template>
  <div class="main">
    <div class="bosh">
      <h1 class="title">Let's get in touch</h1>
      <div class="chiziq"></div>
      <div class="box">
        <div class="in">
          <i class="fa-solid fa-location-dot"></i>
          <h1 class="what">Meet us in person</h1>
          <h2 class="street">8776 Juniper Street</h2>
          <h2 class="home">Unit #204</h2>
          <h2 class="adress">Merriweather, Ontorio,Canada</h2>
        </div>

        <div class="in">
          <i class="fa-regular fa-envelope"></i>
          <h1 class="what">The traditional way</h1>
          <h2 class="street">Email us</h2>
          <h2 class="home">contact@minimal.com</h2>
          <h2 class="adress">Contact form,Scroll down</h2>
        </div>

        <div class="in">
          <i class="fa-regular fa-heart"></i>
          <h1 class="what">Let’s get social</h1>
          <div class="social">
            <h2><i class="fa-brands fa-facebook"></i> Facebook</h2>
            <h2><i class="fa-brands fa-twitter"></i> Twitter</h2>
            <h2><i class="fa-brands fa-linkedin"></i> Linkedin</h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.main {
  width: 100%;
  height: 500px;
  background: #7ec4bd;
  background-image: url("../../public/layer.png");
  .bosh {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    .title {
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px;
      text-transform: uppercase;
      margin-top: 70px;
    }
    .chiziq {
      width: 80px;
      height: 2px;
      background: rgba(0, 0, 0, 0.09);
      margin-bottom: 40px;
    }
    .box {
      widows: 100%;
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 50px;
    }
  }
}
.in {
  widows: 30%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  i {
    font-size: 50px;
  }
  .what {
    color: #333;
    text-align: center;
    font-family: Montserrat;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    text-transform: uppercase;
  }
  .street {
    color: #212121;
    text-align: center;
    font-family: Vollkorn;
    font-size: 17px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px; /* 129.412% */
    margin-bottom: -20px;
  }
  .home {
    color: #212121;
    text-align: center;
    font-family: Vollkorn;
    font-size: 17px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px;
    margin-bottom: -20px;
  }
  .adress {
    color: #212121;
    text-align: center;
    font-family: Vollkorn;
    font-size: 17px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px;
  }
  .social {
    display: flex;
    flex-direction: column;
    i {
      font-size: 14px;
    }
    h2 {
      color: #212121;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: normal;
      font-weight: 400;
      line-height: 20px;
    }
  }
}
</style>

<template>
  <div class="main">
    <div class="bosh">
      <h1 class="title">Our team</h1>
      <div class="chiziq"></div>
      <div class="members">
        <div class="member">
          <img src="../../public/member1.png" alt="member" />
          <h2 class="name">Ron Swanson</h2>
          <h3 class="job">Founder</h3>
          <div class="social">
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-linkedin-in"></i>
            <i class="fa-solid fa-envelope"></i>
          </div>
        </div>

        <div class="member">
          <img src="../../public/member2.png" alt="member" />
          <h2 class="name">Julia Depish</h2>
          <h3 class="job">Marketing</h3>
          <div class="social">
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-linkedin-in"></i>
            <i class="fa-solid fa-envelope"></i>
          </div>
        </div>

        <div class="member">
          <img src="../../public/member3.png" alt="member" />
          <h2 class="name">Danny Devry</h2>
          <h3 class="job">Designer</h3>
          <div class="social">
            <i class="fa-brands fa-square-instagram"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-brands fa-square-behance"></i>
            <i class="fa-solid fa-globe"></i>
            <i class="fa-solid fa-envelope"></i>
          </div>
        </div>

        <div class="member">
          <img src="../../public/member4.png" alt="member" />
          <h2 class="name">Lisa Smith</h2>
          <h3 class="job">Developer</h3>
          <div class="social">
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-twitter"></i>
            <i class="fa-solid fa-envelope"></i>
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
  height: 620px;
  display: flex;
  justify-content: center;
  align-items: center;
  .bosh {
    widows: 100%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    .title {
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px;
      text-transform: uppercase;
    }
    .chiziq {
      width: 80px;
      height: 2px;
      background: rgba(0, 0, 0, 0.09);
      margin-bottom: 43px;
      margin-top: 20px;
    }
    .members {
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      width: 100%;
      gap: 20px;
      .member {
        display: flex;
        flex-direction: column;
        align-items: center;

        .name {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
        }
        .job {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
        }
        .social {
          display: flex;
          flex-direction: row;
          gap: 15px;
        }
      }
    }
  }
}

@media screen and (max-width: 960px) {
  .main {
    width: 100%;
    height: 900px;
  }
}
</style>

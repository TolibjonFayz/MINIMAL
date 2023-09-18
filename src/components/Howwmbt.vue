<template>
  <div class="main">
    <div class="bosh">
      <h1 class="text-h1">How we make brands thrive</h1>
      <div class="chiziq"></div>
      <div class="blogs">
        <div class="blog">
          <div class="imgdiv">
            <img src="../../public/nishon.png" alt="nishon" />
          </div>
          <h1 class="job">SET a target</h1>
          <p class="job-p">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse
            varius enim in eros elementum tristique.
          </p>
        </div>

        <div class="blog">
          <div class="imgdiv">
            <img src="../../public/sms1.png" alt="sms1" />
          </div>
          <h1 class="job">design a solution</h1>
          <p class="job-p">
            Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut
            commodo diam libero vitae erat.
          </p>
        </div>

        <div class="blog">
          <div class="imgdiv">
            <img src="../../public/sms2.png" alt="sms2" />
          </div>
          <h1 class="job">track the progress</h1>
          <p class="job-p">
            LAenean faucibus nibh et justo cursus id rutrum lorem imperdiet.
            Nunc ut sem vitae risus tristique posuere.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.main {
  width: 100%;
  height: 625px;
  display: flex;
  justify-content: center;
  align-items: center;
  .bosh {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    width: 60%;
    height: 487px;
    .text-h1 {
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
    }
    .blogs {
      display: flex;
      flex-direction: row;
      justify-content: center;
      width: 100%;
      gap: 10px;
      .blog {
        display: flex;
        flex-direction: column;
        height: 368px;
        width: 30%;
        justify-content: center;
        align-items: center;
        margin-top: 43px;
        .imgdiv {
          display: flex;
          justify-content: center;
          align-items: center;
          width: 100%;
          height: 50%;
          background: #f5f5f5;
          img {
            width: 127px;
            height: 119px;
          }
        }
        .job {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
        }
        .job-p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 15px;
          font-style: normal;
          font-weight: 400;
          line-height: 22px;
        }
      }
    }
  }
}

@media screen and (max-width: 685px) {
  .main {
    .bosh {
      width: 80%;
      height: 487px;
      .blogs {
        gap: 30px;
      }
    }
  }
}
</style>

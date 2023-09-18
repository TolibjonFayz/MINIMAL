<template>
  <div class="main">
    <div class="bosh">
      <h1 class="title">Recent projects</h1>
      <div class="chiziq"></div>
      <div class="projects">
        <div class="project">
          <img class="p-img" src="../../public/img1.png" alt="img1" />
          <h1 class="p-name">woods</h1>
          <h5 class="p-p">Photography</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img2.png" alt="img1" />
          <h1 class="p-name">Path</h1>
          <h5 class="p-p">Website • Photography</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img3.png" alt="img1" />
          <h1 class="p-name">darkness</h1>
          <h5 class="p-p">Website</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img4.png" alt="img1" />
          <h1 class="p-name">waves</h1>
          <h5 class="p-p">Photography</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img5.png" alt="img1" />
          <h1 class="p-name">drops</h1>
          <h5 class="p-p">Website</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img6.png" alt="img1" />
          <h1 class="p-name">ocean</h1>
          <h5 class="p-p">Website</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img7.png" alt="img1" />
          <h1 class="p-name">town</h1>
          <h5 class="p-p">Website</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img8.png" alt="img1" />
          <h1 class="p-name">mountain</h1>
          <h5 class="p-p">Website</h5>
        </div>

        <div class="project">
          <img class="p-img" src="../../public/img9.png" alt="img1" />
          <h1 class="p-name">camera</h1>
          <h5 class="p-p">Website</h5>
        </div>
      </div>
    </div>
  </div>
  <br />
</template>

<script></script>

<style lang="scss" scoped>
.main {
  width: 100%;
  height: 1600px;
  flex-shrink: 0;
  background: #f5f5f5;
  display: flex;
  justify-content: center;
  .bosh {
    display: flex;
    flex-direction: column;
    width: 70%;
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
      margin-top: 60px;
      &:hover {
        transition: all 0.3s linear;
        color: #111;
      }
    }
    .chiziq {
      width: 80px;
      height: 2px;
      flex-shrink: 0;
      background: rgba(0, 0, 0, 0.09);
      margin-top: 28px;
      margin-bottom: 43px;
      &:hover {
        transition: all 0.3s linear;
        background: #333;
        width: 200px;
      }
    }
    .projects {
      display: flex;
      flex-direction: row;
      flex-wrap: wrap;
      width: 100%;
      gap: 20px;
      align-items: center;
      justify-content: center;
      .project {
        width: 30%;
        display: flex;
        flex-direction: column;
        background: #fff;
        justify-content: space-around;
        &:hover {
          transition: all 0.3s linear;
          scale: 0.95;
          cursor: pointer;
        }
        .p-img {
          width: 100%;
        }
        .p-name {
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
          margin-top: 19px;
        }
        .p-p {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
        }
      }
    }
  }
}

@media screen and (max-width: 960px) {
  .main {
    height: 1200px;
  }
}

@media screen and (max-width: 685px) {
  .main {
    width: 100%;
    height: 1000px;
  }
}
</style>

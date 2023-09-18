<template>
  <div class="main">
    <img src="../../public/x.png" alt="x" />
    <h2 class="main-h1">
      Minimalist is a full-service digital creative agency located in Ontorio
      Canada. We focus on design, consulting, technology, and photography. We’ve
      been building unique digital products, platforms, and experiences for the
      past 6 years. Let us help your company grow.
    </h2>
    <button>Get in touch</button>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.main {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 100%;
  height: 289px;
  flex-shrink: 0;
  background: #fefec9;
  img {
    width: 52px;
    height: 52px;
    flex-shrink: 0;
    margin-top: -25px;
  }
  .main-h1 {
    width: 70%;
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 25px;
    margin-top: 30px;
  }
  button {
    widows: 150px;
    height: 50px;
    border: 1px solid #47474f;
    background-color: inherit;
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px;
    padding: 13px 34px;
    margin-top: 30px;
    &:hover {
      background-color: #47474f;
      color: #fefec9;
      transition: all 0.2s linear;
    }
  }
}
@media screen and (max-width: 685px) {
  .main {
    height: 350px;
  }
}

@media screen and (max-width: 460px) {
  .main {
    height: 400px;
  }
}

@media screen and (max-width: 370px) {
  .main {
    height: 450px;
  }
}
</style>

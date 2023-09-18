<template>
  <div class="main">
    <div class="bosh">
      <div class="inputs">
        <input class="name" type="text" placeholder="Name" />
        <input class="email" type="email" placeholder="Email" />
        <input class="budget" type="text" placeholder="Budget" />
        <textarea
          class="textarea"
          cols="30"
          rows="10"
          placeholder="Describe your project..."
        ></textarea>
      </div>
      <button class="button">Send Message</button>
      <img class="logo" src="../../public/logo.png" alt="logo" />
      <h1 class="bottomest">
        Minimal Template made in Webflow. All rights reserved.
      </h1>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.main {
  width: 100%;
  height: 650px;
  background-color: #000;
  display: flex;
  justify-content: center;
  align-items: center;
}

.bosh {
  margin-top: 50px;
  margin-bottom: 50px;
  width: 50%;
  display: flex;
  flex-direction: column;
  gap: 50px;
  justify-content: space-between;
  align-items: center;
  .inputs {
    display: flex;
    flex-direction: column;
    width: 100%;
    justify-content: center;
    align-items: center;
    .name {
      width: 80%;
      background: rgba(255, 255, 255, 0.18);
      border: none;
      padding: 15px 30px;
      color: #fff;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
    }
    .email {
      width: 80%;
      background: rgba(255, 255, 255, 0.2);
      border: none;
      padding: 15px 30px;
      color: #fff;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
    }
    .budget {
      width: 80%;
      background: rgba(255, 255, 255, 0.18);
      border: none;
      padding: 15px 30px;
      color: #fff;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
    }
    .textarea {
      width: 80%;
      height: 127px;
      background: rgba(255, 255, 255, 0.2);
      color: #fff;
      font-family: Vollkorn;
      font-size: 17px;
      font-style: italic;
      font-weight: 400;
      line-height: 22px;
      border: none;
      resize: none;
      padding: 15px 30px;
    }
  }
  .button {
    padding: 15px 60px;
    background: inherit;
    color: #8bcac3;
    text-align: center;
    font-family: Vollkorn;
    font-size: 17px;
    font-style: italic;
    font-weight: 400;
    line-height: 22px;
    border: 1px solid #7ec4bd;
    cursor: pointer;
    &:hover {
      background-color: #7ec4bd;
      color: black;
      transition: all 0.2s linear;
    }
  }
  .logo {
    width: 43px;
    height: 46px;
  }
  .bottomest {
    color: rgba(255, 255, 255, 0.4);
    text-align: center;
    font-family: Vollkorn;
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    line-height: 22px;
  }
}

@media screen and (max-width: 450px) {
  .bosh {
    margin-top: 50px;
    margin-bottom: 0;
    width: 80%;
    display: flex;
    flex-direction: column;
    gap: 30px;
    justify-content: space-between;
    align-items: center;
  }
}
</style>

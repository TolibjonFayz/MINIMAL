<template>
  <div class="navbar">
    <div class="logo">
      <img class="image" :src="image1" alt="Logo" />
      <h1 class="minimal">Minimal</h1>
    </div>
    <div class="texts">
      <h2>process</h2>
      <h2>projects</h2>
      <h2>team</h2>
      <h2>contact</h2>
    </div>
  </div>
</template>

<script setup>
import image1 from "../../public/logo.png";
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  flex-direction: row;
  width: 100%;
  height: 106px;
  justify-content: center;
  gap: 400px;
  .logo {
    display: flex;
    flex-direction: row;
    gap: 50px;

    .image {
      width: 65px;
      height: 70px;
      flex-shrink: 0;
      padding-top: 5px;
    }
    .minimal {
      color: #333;
      font-family: Oswald;
      font-size: 22px;
      font-style: normal;
      font-weight: 400;
      line-height: 38px;
      text-transform: uppercase;
      width: 72px;
    }
  }
  .texts {
    display: flex;
    height: 45px;
    padding: 23px 0px 0px 34px;
    justify-content: flex-end;
    align-items: flex-start;
    gap: 34px;
    h2 {
      color: #404040;
      font-family: Montserrat;
      font-size: 12px;
      font-style: normal;
      font-weight: 400;
      line-height: 20px;
      text-transform: uppercase;
      &:hover {
        transition: all 0.3s linear;
        cursor: pointer;
      }
    }
  }
}
</style>

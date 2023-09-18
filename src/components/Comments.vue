<template>
  <div class="main">
    <div class="bosh">
      <div><i class="fa-solid fa-quote-left"></i></div>
      <div class="comments">
        <div class="comment one">
          <h1 class="h1">
            “I love these guys! They did a great job. I would recommend them to
            anyone.”
          </h1>
          <img src="../../public/comment1.png" alt="" />
          <h2 class="name">Julius Von Uberstien</h2>
        </div>
        <div class="comment">
          <h1 class="h1">
            “Elexis Corp. has grown immensely with the help of Minimal.”
          </h1>
          <img src="../../public/comment2.png" alt="" />
          <h2 class="name">Rachel Stamos</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.main {
  display: flex;
  width: 100%;
  height: 500px;
  background: #f5f5f5;
  justify-content: center;
  align-items: center;
  .bosh {
    display: flex;
    width: 60%;
    height: 373px;
    display: flex;
    flex-direction: column;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    .comments {
      display: flex;
      flex-direction: row;
      justify-content: center;
      .one {
        border-right: 1px solid #ababab;
      }
      .comment {
        width: 40%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        .h1 {
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 26px;
          font-style: normal;
          font-weight: 400;
          line-height: 33px;
        }
        img {
          width: 64px;
          height: 64px;
        }
        .name {
          color: #ababab;
          text-align: center;
          font-family: Montserrat;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
        }
      }
    }
  }
}

@media screen and (max-width: 450px) {
  .bosh {
    width: 80%;
    height: 380px;
    .comments {
      width: 150%;
      justify-content: space-between;
      .comment {
        width: 50%;
        .h1 {
          font-size: 20px;
        }
        img {
          width: 64px;
          height: 64px;
        }
        .name {
          font-size: 12px;
        }
      }
    }
  }
}
</style>

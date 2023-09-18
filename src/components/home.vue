<template>
  <div>
    <section class="section">
      <div class="container">
        <img class="img" src="../assets/icon/image4.svg" alt="" />
        <ul>
          <li>
            <p class="p">
              “I love these guys! They did a great job. I would recommend them
              to anyone.”
            </p>
            <img src="../assets/img/image15.png" alt="" />
            <p>Julius Von Uberstien</p>
          </li>
          <li>
            <p class="p">
              “I love these guys! They did a great job. I would recommend them
              to anyone.”
            </p>
            <img src="../assets/img/image15.png" alt="" />
            <p>Julius Von Uberstien</p>
          </li>
        </ul>
      </div>
    </section>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
.section {
  width: 1440px;
  height: 511px;
  flex-shrink: 0;
  background: #f5f5f5;
  .container {
    max-width: 100%;
    width: 1000px;
    padding: 0 20px;
    margin: 0 auto;

    .img{
      margin:69px 450px 0px 490px;
      // display: flex;
      // align-items:center;
      // justify-content: space-between;
    }

    ul {
      width: 893px;
      height: 274px;
      list-style-type: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap:10px;
    
      li {
        margin: 19px 0px 8px 2px;
        width: 446.5px;
        height: 215px;
        flex-shrink: 0;
        margin:119px 20px 20px  0px;

        .p {
          width: 338px;
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
          flex-shrink: 0;
          background: url(<path-to-image>), lightgray 50% / cover no-repeat;
          margin: 24px 191px 10px 241px;
        }
        p {
          width: 181px;
          color: #ababab;
          text-align: center;
          font-family: Montserrat;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
          margin: 10px 133px 0px 141px;
        }
      }
    }
  }
}
</style>
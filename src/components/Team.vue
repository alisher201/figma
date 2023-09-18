<template>
  <div>
    <section class="section">
      <div class="container">
        <h2>Our Team</h2>
        <ul>
          <li>
            <img class="img" src="../assets/img/image14.png" alt="" />
            <p>Ron Swanson</p>
            <p>Founder</p>
            <div>
              <img class="image" src="../assets/icon/icon1.svg" alt="" />
              <img class="image" src="../assets/icon/icon2.svg" alt="" />
              <img class="image" src="../assets/icon/icon3.svg" alt="" />
            </div>
          </li>
          <li>
            <img class="img" src="../assets/icon/image2.png" alt="" />
            <p>Ron Swanson</p>
            <p>Founder</p>
            <div>
              <img class="image" src="../assets/icon/icon1.svg" alt="" />
              <img class="image" src="../assets/icon/icon2.svg" alt="" />
              <img class="image" src="../assets/icon/icon3.svg" alt="" />
            </div>
          </li>
          <li>
            <img class="img" src="../assets/icon/image3.png" alt="" />
            <p>Ron Swanson</p>
            <p>Founder</p>
            <div>
              <img class="image" src="../assets/icon/icon1.svg" alt="" />
              <img class="image" src="../assets/icon/icon2.svg" alt="" />
              <img class="image" src="../assets/icon/icon3.svg" alt="" />
              
            </div>
          </li>
          <li>
            <img class="img" src="../assets/icon/image3.png" alt="" />
            <p>Ron Swanson</p>
            <p>Founder</p>
            <div>
              <img class="image" src="../assets/icon/icon1.svg" alt="" />
              <img class="image" src="../assets/icon/icon2.svg" alt="" />
              <img class="image" src="../assets/icon/icon3.svg" alt="" />
              
            </div>
          </li>
        </ul>
      </div>
    </section>
  </div>
</template>

<script>
</script>

<style lang="scss" scoped>
.section {
  width: 1440px;
  height: 600px;
  flex-shrink: 0;
  background: #fff;

  .container {
    max-width: 100%;
    width: 1000px;
    padding: 0 20px;
    margin: 0 auto;

    h2 {
      width: 129px;
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px; /* 156.522% */
      text-transform: uppercase;
      margin: 11px 656px 73px 370px;
      // display: flex;
      // align-items: center;
      // justify-content: space-between;
    }
    ul {
      margin: 69px 250px 69px 0px;
      width: 940px;
      height: 478px;
      flex-shrink: 0;
      list-style-type: none;

      display: flex;
      align-items: center;
      justify-content: center;

      li {
        gap: 90px;
        .img {
          width: 220px;
          height: 220px;
          flex-shrink: 0;
          background: url(<path-to-image>), lightgray 50% / cover no-repeat;
      
        }
        p {
          width: 131px;
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
          margin: 20px 54px 6px 54px;
        }
        div {
          width: 150px;
          display: flex;
          background-color: red;
          margin-left: 30px;
          align-items: center;
          // justify-content:center
          .image {
            padding: 15px;
            margin-right: 10px;
            display: flex;
          }
        }
      }
    }
  }
}
</style>
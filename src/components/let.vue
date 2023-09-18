<template>
  <div>
    <section class="section">
      <div class="container">
        <h2>LET’s Get in touch</h2>
        <ul>
          <li>
            <img src="../assets/icon/image5.svg" alt="" />
            <p class="p">MEET US IN PERSON</p>
            <p>8776 Juniper Street</p>
            <p>Unit #204</p>
            <p>Merriweather, Ontorio</p>
            <p>Canada</p>
          </li>
          <li>
            <img src="../assets/icon/image6.svg" alt="" />
            <p class="p">MEET US IN PERSON</p>
            <p>Email us</p>
            <p>contact@minimal.com</p>
            <p>Contact form</p>
            <p>Scroll down</p>
          </li>
          <li>
            <img src="../assets/icon/image7.svg" alt="" />
            <p class="p">MEET US IN PERSON</p>
            <p>8776 Juniper Street</p>
            <p>Unit #204</p>
            <p>Merriweather, Ontorio</p>
            <p>Canada</p>
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
  height: 517px;
  flex-shrink: 0;
  //   background: url(<path-to-image>), rgb(15, 156, 233) 50% / cover no-repeat,
  //     #7ec4bd;
  background-color: rgb(34, 231, 231);
  .container {
    max-width: 100%;
    width: 1000px;
    // padding: 0 20px;
    // margin: 0 auto;
    // background-color: red;
    // margin: 69px 250px 69px 250px;

    h2 {
      margin: 10px 347px 73px 347px;
      width: 245px;
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px; /* 156.522% */
      text-transform: uppercase;
    }
    ul {
      list-style-type: none;
      margin-top: 73px;
      display: flex;
      width: 960px;
      height: 260px;
      padding-right: 0px;
      justify-content: center;
      align-items: flex-start;
      flex-shrink: 0;
      margin:73px 250px 70px 0px;
      li {
        width: 319.984px;
        height: 278px;
        flex-shrink: 0;
        // background-color: white;

        img {
          width: 44px;
          height: 65px;
          flex-shrink: 0;
          background: url(<path-to-image>), lightgray 50% / cover no-repeat;
          margin: 13px 137px 26px 137px;
        }
        .p {
          width: 173px;
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
          margin: 20px 73px 20px 73px;
        }
        p {
          width: 144px;
          color: #212121;
          text-align: center;
          font-family: Vollkorn;
          font-size: 17px;
          font-style: normal; 
          font-weight: 400;
          line-height: 22px; 
          display: flex;
          align-items: center;
          justify-content: center;
          margin-left:81px;
        }
      }
    }
  }
}
</style>
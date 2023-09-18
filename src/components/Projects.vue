<template>
  <div>
    <section class="section">
      <div>
        <h2>Recent projects</h2>
        <ul>
          <li>
            <img src="../assets/img/image13.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image5.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image6.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
        </ul>
        <ul>
          <li>
            <img src="../assets/img/image7.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image8.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image9.png" alt="" />
           
              <p class="p">woods</p>
              <p>Photography</p>
           
          </li>
        </ul>
        <ul>
          <li>
            <img src="../assets/img/image10.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image11.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
          </li>
          <li>
            <img src="../assets/img/image12.png" alt="" />
            <p class="p">woods</p>
            <p>Photography</p>
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
  height: 1469px;
  flex-shrink: 0;
  background: #f5f5f5;

  div {
    margin: 69px 250px 69px 250px;
    h2 {
      margin: 10px 355px 73px 355px;
      width: 230px;
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px; /* 156.522% */
      text-transform: uppercase;
      display: flex;
      //   align-items: center;
      justify-content: center;
    }
    ul {
      list-style-type: none;
      display: flex;
      li {
        // margin: 119px 20px 20px 250px;
        // border:1px solid green;
        box-shadow: 2px 2px green;
        padding: 15px;
        // background-color: red;
        background: #FFF;
        :hover{
          box-shadow: 5px 5px;
        }
        img {
          width: 300px;
          height: 300px;
          flex-shrink: 0;
          background: url(<path-to-image>), lightgray 50% / cover no-repeat;
        }
        
        .p {
          width: 69px;
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
          justify-content: center;
          margin: 19px 121px 4px 120px;
          //   background-color: red;
        }
        p {
          width: 84px;
          color: #333;
          text-align: center;
          font-family: Vollkorn;
          font-size: 14px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          margin: 4px 108px 21px 108px;
        }
      }
    }
  }
}
</style>
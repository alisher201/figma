<template>
  <div>
    <section class="section ">
      <h2>How we make brands thrive</h2>
      <ul>
        <li>
          <img src="../assets/img/image4.png" alt="" />
          <p class="p">SET a target</p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            repellendus aperiam vel possimus aspernatur illo?
          </p>
        </li>
        <li>
          <img src="../assets/img/image2.png" alt="" />
          <p class="p">SET a target</p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            repellendus aperiam vel possimus aspernatur illo?
          </p>
        </li>
        <li>
          <img src="../assets/img/image3.png" alt="" />
          <p class="p">SET a target</p>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            repellendus aperiam vel possimus aspernatur illo?
          </p>
        </li>
      </ul>
    </section>
    <div></div>
  </div>
</template>

<script>
</script>

<style lang="scss" scoped>
div {
  background-color: antiquewhite;
  width: 1440px;
  max-width: 1800px;

  .section {
    margin: 0px 0px 0px 200px;
    // background-color: red;
    width: 1080px;
    h2 {
      width: 394px;
      color: #333;
      text-align: center;
      font-family: Montserrat;
      font-size: 23px;
      font-style: normal;
      font-weight: 400;
      line-height: 36px;
      text-transform: uppercase;
      margin: 10px 273px 73px 273px;
      border: 2px solid black;
    }
    ul {
      display: flex;
      list-style-type: none;
      // align-items: center;
      // justify-content: space-between;
      li {
        margin:73px 10px 38px 10px;
        img {
          padding: 50px 86px 50px 87px;
          width: 300px;
          height: 219px;
          flex-shrink: 0;
          background: #f5f5f5;
          gap: 20px;
        }
        .p {
          margin: 38px 100px 20px 100px;
          width: 119px;
          color: #333;
          text-align: center;
          font-family: Montserrat;
          font-size: 16px;
          font-style: normal;
          font-weight: 400;
          line-height: 20px;
          text-transform: uppercase;
        }
        p {
          margin: 20px 12px 5px 11px;
          width: 297px;
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
</style>
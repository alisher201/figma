<template >
  <div>
    <section>
      <img src="../assets/img/image1.png" alt="" />
      <div class="wrapper">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum id
          officia sint laudantium ab odit ratione enim laborum deserunt
          doloremque ullam alias libero, suscipit, qui cum ducimus repellat,
          nisi voluptatibus dignissimos. Voluptas ipsam sequi impedit ea porro
          quidem labore possimus!
        </p>
        <button>Get in Touch</button>
      </div>
    </section>
  </div>
</template>

<script setup>
import img from "../assets/img/image1.png";
</script>

<style lang="scss" scoped>

img {
  width: 1440px;
  height: 641px;
  flex-shrink: 0;
  background: url(<path-to-image>), lightgray 50% / cover no-repeat;
  
}


.wrapper {
  width: 1440px;
  height: 289px;
  position: relative;
  //   flex-shrink: 0;
  background-color: #fefec9;
  p {
    width: 70%;
    margin: 64px 250px 40px 250px;
    position: absolute;
    background-color: aqua;
    width: 940px;
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 18px;
    font-style: normal;
    font-weight: 400;
    line-height: 25px; /* 138.889% */
    padding:8px;
  }
  button {
    margin: 175px 641px 61px 641px;
    padding: 13px 34px 20px 34px;
    width: 181px;
    color: #47474f;
    text-align: center;
    font-family: Vollkorn;
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 20px; /* 125% */
  background-color: #fefec9;

  }
}
</style>
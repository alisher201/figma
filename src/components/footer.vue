<template>
  <div>
    <section class="section">
      <div class="container">
        <div class="wrapper">
          <input type="text" placeholder="Name" />
          <input type="text" placeholder="Email" />
          <input type="text" placeholder="Budget" />
          <input type="text" placeholder="describe your project" />
          <button>Send Message</button>

          <img src="../assets/icon/IMAGE.svg" alt="" />
          <p>Minimal Template made in Webflow. All rights reserved.</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
</script>

<style lang="scss" scoped>
div {
  width: 1440px;
  height: 639px;
  flex-shrink: 0;
  background: #000;
  .container {
    max-width: 100%;
    width: 1000px;
    margin: 0 auto;
    padding: 0 20px;
    .wrapper {
      display: flex;
      width: 940px;
      padding: 0px 188px 5.953px 188px;
      flex-direction: column;
      align-items: center;
      gap: 15.047px;
      //   margin:69px 250px 69px 0px;
      //   border: 4px solid white;
      input {
        // margin:10px;
        width: 564px;
        height: 57px;
        flex-shrink: 0;
        background-color: rgb(67, 64, 64);
        font-size: 40px;
      }
      button {
        margin: 23px 176px 24px 176px;
        padding: 25px;
        width: 200px;
        background-color: black;
        color: #8bcac3;
        text-align: center;
        font-family: Vollkorn;
        font-size: 17px;
        font-style: italic;
        font-weight: 400;
        line-height: 22px;
        border: 2px solid;
      }
      p {
        width: 391px;
        color: rgba(255, 255, 255, 0.4);
        text-align: center;
        font-family: Vollkorn;
        font-size: 15px;
        font-style: normal;
        font-weight: 400;
        line-height: 22px; /* 146.667% */
      }
    }
  }
}
</style>
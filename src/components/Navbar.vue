<template>
  <div>
    <header>
      <div class="container">
        <nav>
          <ul>
            <li>
              <img src="../assets/img/IMAGE.svg" alt="" />
              <h3>Minimal</h3>
            </li>
            <li>
              <p>process</p>
              <p>projects</p>
              <p>team</p>
              <p>contact</p>
            </li>
          </ul>
        </nav>
      </div>
    </header>
  </div>
</template>

<script setup>
import img from "../assets/img/IMAGE.svg";
</script>
<style lang="scss" scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  padding: 35px;
  width: 1440px;
  position: fixed;
  top: 0;
  z-index: 10;
  height: 156px;
  flex-shrink: 0;
  background: #fff;
  border:2px solid green;
  //   background-color: black;

  ul {
    display: flex;
    align-items: center;
    justify-content: space-between;

    li {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 50px;
      p {
        width: 60px;
        color: #404040;
        font-family: Montserrat;
        font-size: 12px;
        font-style: normal;
        font-weight: 400;
        line-height: 20px; /* 166.667% */
        text-transform: uppercase;
      }
    }
  }
}
</style>
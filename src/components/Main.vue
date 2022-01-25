<template>
  <main>
    <div class="jumbo_container container-fluid">
      <img class="train" src="../assets/images/slider_slide3_img2.png" alt="" />
      <img
        class="costruzioni"
        src="../assets/images/slider_slide3_img3.png"
        alt=""
      />
      <div class="rectangle1"></div>
      <div class="rectangle2"></div>
      <div class="rectangle3"></div>
      <p class="handlee">Learnin & fun</p>
    </div>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss">
.jumbo_container {
  position: relative;
  height: 800px;
  width: 100vw;
  background-image: url(../assets/images/slider_slide3_background.png);
  background-size: contain;
}
.train {
  position: absolute;
  top: 39vh;
  left: 40vw;
}
.costruzioni {
  position: absolute;
  top: 44vh;
  left: 73vw;
}
.rectangle1 {
  position: absolute;
  top: 53vh;
  left: 47vw;
  width: 30px;
  height: 10px;
  border: 2px solid #FD6500;
}
.rectangle2 {
  position: absolute;
  top: 53vh;
  left: 49vw;
  width: 30px;
  height: 10px;
  border: 2px solid #FD6500;
}
.rectangle3 {
  position: absolute;
  top: 52vh;
  left: 51vw;
  width: 30px;
  height: 10px;
  border: 2px solid #FD6500;
}
.handlee{
  font-family: 'Handlee', cursive;
  font-size: 40px;
  color: #EDE7E4;
  position: absolute;
  top: 20vh;
  left: 20vw;
}
</style>

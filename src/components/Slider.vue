.
<template>
  <div class="col-6">
    <div class="prev">
      <img src="../assets/images/slider_previous.png" alt="" />
    </div>
    <div class="slider_wrap">
      <img class="img-fluid" src="../assets/slider/1.jpg" alt="" />
    </div>
    <div class="next"></div>
  </div>
</template>

<script>
export default {
  name: "Slider",
  data() {
    return {
      counter: null,
    };
  },
};
</script>

<style lang="scss">
.slider_wrap {
  position: relative;
  width: 100%;
  height: 70%;
  margin: auto;
}

.prev,
.next {
    color: black;
    z-index: 10;
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  background-color: #fe6500;
}
</style>

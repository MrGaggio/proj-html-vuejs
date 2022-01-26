.
<template>
  <div class="col-6">
    <div class="slider_wrap d-flex">
      <img class="img-fluid" :src="`../assets/slider/${images[counter]}`" />

      <div @click="prev" class="prev">
        <img src="../assets/images/slider_previous.png" alt="" />
      </div>
      <div @click="next" class="next">
        <img src="../assets/images/slider_next.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Slider",
  data() {
    return {
      counter: 0,
      images: ["1.jpg", "2.jpg", "3.jpg", "4.jpg", "5.jpg", "6.jpg"],
    };
  },
  methods: {
    prev() {
      this.counter -= 1;
      if (this.counter < 0) {
        this.counter = this.images.length - 1;
      }
    },
    next() {
      this.counter += 1;
      if (this.counter > this.images.length - 1) {
        this.counter = 0;
      }
    },
  },
};
</script>

<style lang="scss">
.slider_wrap {
  position: relative;
  width: 90%;
  height: auto;
  margin: auto;
}

.prev {
  display: flex;
  position: absolute;
  top: 200px;
  background-color: #fe6500;
}

.next {
  position: absolute;
  top: 200px;
  right: 0%;
  background-color: #fe6500;
}
</style>

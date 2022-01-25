<template>
  <main>
    <section class="jumbo_section">
      <div class="jumbo_container container-fluid">
        <img
          class="train"
          style="position: relative"
          src="../assets/images/slider_slide3_img2.png"
          alt=""
        />
        <div class="rectangle1"></div>
        <div class="rectangle2"></div>
        <div class="rectangle3"></div>

        <img
          class="costruzioni"
          src="../assets/images/slider_slide3_img3.png"
          alt=""
        />

        <p class="handlee">Learnin & fun</p>
      </div>
      <div class="how_to">
        <div class="container">
          <div class="row py-5">
            <div class="col-9">
              <p>How to Enroll Your Child to a Class?</p>
            </div>
            <div class="col-3">
              <button type="button" class="btn btn-outline-light ps-3 pe-0">
                LEARN MORE
                <span
                  ><img
                    style="width: 30px"
                    src="../assets/images/slider_next.png"
                    alt=""
                /></span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="welcome_to_fable">
      <div class="container title mt-5">
        <div class="row">
          <div class="col">
            <h1 class="text-center">Welcome to Fable</h1>
            <p class="text-center">
              Fable daycare, preschool, and kindergarten
            </p>
            <div class="divider text-center mb-5">
              <img src="../assets/images/header_divider.png" alt="" />
            </div>
          </div>
        </div>
      </div>
      <div class="container container_circle">
        <div class="row">
          <div class="col-3">
            <div class="circle_png">
              <img src="" alt="" />
            </div>
            <h3></h3>
            <p></p>
          </div>
          <div class="col-3">
            <div class="circle_png">
              <img src="" alt="" />
            </div>
            <h3></h3>
            <p></p>
          </div>
          <div class="col-3">
            <div class="circle_png">
              <img src="" alt="" />
            </div>
            <h3></h3>
            <p></p>
          </div>
          <div class="col-3">
            <div class="circle_png">
              <img src="" alt="" />
            </div>
            <h3></h3>
            <p></p>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss">
main {
  font-family: "Almarai", sans-serif;
}

.how_to p {
  color: #efedf6;
  font-weight: 100;
  font-size: 35px;
}
.jumbo_container {
  position: relative;
  height: 800px;
  width: 100vw;
  background-image: url(../assets/images/slider_slide3_background.png);
  background-size: contain;
}
.train_container {
  position: relative;
}
.train {
  position: absolute;
  top: 39vh;
  left: 37vw;
}
.costruzioni {
  position: absolute;
  top: 44vh;
  left: 73vw;
}
.rectangle1 {
  position: absolute;
  top: 53vh;
  left: 42vw;
  width: 30px;
  height: 10px;
  border: 2px solid #fd6500;
}
.rectangle2 {
  position: absolute;
  top: 53vh;
  left: 44vw;
  width: 30px;
  height: 10px;
  border: 2px solid #fd6500;
}
.rectangle3 {
  position: absolute;
  top: 52vh;
  left: 46vw;
  width: 30px;
  height: 10px;
  border: 2px solid #fd6500;
}
.handlee {
  font-family: "Handlee", cursive;
  font-size: 40px;
  color: #ede7e4;
  position: absolute;
  top: 20vh;
  left: 25vw;
}
.how_to {
  height: 150px;
  background-image: url(../assets/images/pattern.png);
}
.circle_png {
  height: 50px;
  width: 50px;
  background-color: #fe6500;
  border-radius: 50%;
}
</style>

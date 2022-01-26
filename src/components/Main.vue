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

      <div class="container cards">
        <div class="row">
          <div class="col">
            <div class="circle_orange">
              <img
                src="../assets/images/schoolbag_alt.png"
                class="card-img-top"
                alt=""
              />
            </div>
            <div class="card" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title text-center mb-4 mt-2">Morbi Etos</h5>
                <p class="card-text text-center">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="circle_purple">
              <img
                src="../assets/images/stroller_alt.png"
                class="card-img-top"
                alt=""
              />
            </div>
            <div class="card" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title text-center mb-4 mt-2">Congue Gravida</h5>
                <p class="card-text text-center">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="circle_orange">
              <img
                src="../assets/images/globe_alt.png"
                class="card-img-top"
                alt=""
              />
            </div>
            <div class="card" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title text-center mb-4 mt-2">Maecenas Node</h5>
                <p class="card-text text-center">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
              </div>
            </div>
          </div>
          <div class="col">
            <div class="circle_purple">
              <img
                src="../assets/images/bell_alt.png"
                class="card-img-top"
                alt=""
              />
            </div>
            <div class="card" style="width: 18rem">
              <div class="card-body">
                <h5 class="card-title text-center mb-4 mt-2">Praesent Morbi</h5>
                <p class="card-text text-center">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="ourphylosophy">
      <div class="container philosophy pt-5 mt-5">
        <div class="row">
          <div class="col-6">
            <p style="display: inline-block" class="overview text-center">
              Overview
            </p>
            <p style="display: inline-block" class="mission text-center">
              Our Mission
            </p>
            <h2 class="fs-1 mb-5 mt-4">
              Our philosophy is learning through play as we offer a stimulating
              evironment for children.
            </h2>
            <div class="full_day d-flex">
              <div class="clock_container pe-5">
                <div class="clock">
                  <img
                    class="card-img-top"
                    src="../assets/images/clock_alt.png"
                    alt=""
                  />
                </div>
              </div>
              <div class="session">
                <h3>Full Day Session</h3>
                <p class="mt-4">
                  pulvinar est metro ligula blandit maecenas return gravida
                  cuprum. Maecenas node. estibulum
                </p>
              </div>
            </div>

            <div class="full_day d-flex mt-5">
              <div class="clock_container pe-5">
                <div class="clock">
                  <img
                    class="card-img-top"
                    src="../assets/images/clock_alt.png"
                    alt=""
                  />
                </div>
              </div>
              <div class="session">
                <h3>Varied Classes</h3>
                <p class="mt-4">
                  pulvinar est metro ligula blandit maecenas return gravida
                  cuprum. Maecenas node. estibulum
                </p>
              </div>
            </div>
          </div>

          <Slider />
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import Slider from "./Slider.vue";
export default {
  name: "Main",
  components: {
    Slider,
  },
};
</script>

<style lang="scss">
main {
  font-family: "Almarai", sans-serif;
  h1,
  h2,
  h3,
  h4,
  h5 {
    color: #56509f;
  }
  p {
    color: #b0b0b0;
  }
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

.welcome_to_fable {
  height: 800px;
}
.welcome_to_fable h1,
h5 {
  color: #56509f;
  font-weight: 800;
}
.welcome_to_fable p {
  color: #7c7c7c;
  font-weight: 700;
}
.card {
  border: none !important;
}
.circle_orange {
  position: relative;
  height: 200px;
  width: 200px;
  background-color: #fe6500;
  border-radius: 50%;
  margin: auto;
}
.circle_purple {
  position: relative;
  height: 200px;
  width: 200px;
  background-color: #56509f;
  border-radius: 50%;
  margin: auto;
}

.card-img-top {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 35% !important;
}

/*
******************
PHYLOSOPHY SECTION
******************
*/

.philosophy {
  background-color: #f5f5f5;
  height: 800px;
}
.overview {
  width: 150px;
  height: 50px;
  line-height: 50px;
  background-color: #fe6500;
  color: white;
  margin-right: 20px;
}
.mission {
  width: 150px;
  height: 50px;
  line-height: 50px;
  color: #b9b9b9;
  border-bottom: 1px solid #b9b9b9;
}
.clock {
  position: relative;
  height: 100px;
  width: 100px;
  background-color: #fe6500;
  border-radius: 50%;
  margin: auto;
}
</style>

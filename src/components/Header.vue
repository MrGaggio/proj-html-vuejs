<template>
  <div class="container">
    <div class="row justify-content-between">
      <div class="col-4 logo_wrap">
        <img
          class="header_icons"
          src="../assets/images/logo.png"
          alt=""
          width="175"
          height=""
        />
      </div>
      <div class="col-8">
        <ul class="nav text-center">
          <li class="nav-item">
            <img class="header_icons" src="../assets/images/home.png" alt="" />
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <img
              class="header_icons"
              src="../assets/images/document.png"
              alt=""
            />
            <a class="nav-link" href="#">Pages</a>
          </li>
          <li class="nav-item">
            <img
              class="header_icons"
              src="../assets/images/printer.png"
              alt=""
            />
            <a class="nav-link" href="#">Blog</a>
          </li>
          <li class="nav-item">
            <img class="header_icons" src="../assets/images/cart.png" alt="" />
            <a class="nav-link" href="#">Shop</a>
          </li>
          <li class="nav-item">
            <img class="header_icons" src="../assets/images/lab.png" alt="" />
            <a class="nav-link" href="#">Shortcodes</a>
          </li>
          <li class="nav-item">
            <img class="header_icons" src="../assets/images/chat.png" alt="" />
            <a class="nav-link" href="#">Support</a>
          </li>
          <li class="nav-item">
            <img
              class="header_icons"
              src="../assets/images/envelope.png"
              alt=""
            />
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss">
#header {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.nav {
  flex-wrap: nowrap !important;
}

li.nav-item {
  padding-top: 36px;
  margin-right: 20px;
 
}
li.nav-item:hover {
  background-color: #fd6500;
}
li a {
  margin-top: 8px;
}
img.header_icons {
  color: #56509f;
 
}
a {
  color: #56509f !important;
}
</style>

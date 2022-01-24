<template>
  <div class="header">
    <div class="logo_container">
      <img class="logo" src="../assets/images/logo.png" alt="" />
    </div>
    <div class="nav">
      <ul>
        <li>
          <img class="header_icons" src="../assets/images/home.png" alt="" />
          <a href="#">Home</a>
        </li>
        <li>
          <img
            class="header_icons"
            src="../assets/images/document.png"
            alt=""
          />
          <a href="#">Pages</a>
        </li>
        <li>
          <img class="header_icons" src="../assets/images/printer.png" alt="" />
          <a href="#">Blog</a>
        </li>
        <li>
          <img class="header_icons" src="../assets/images/cart.png" alt="" />
          <a href="#">Shop</a>
        </li>
        <li>
          <img class="header_icons" src="../assets/images/lab.png" alt="" />
          <a href="#">Shortcodes</a>
        </li>
        <li>
          <img src="../assets/images/chat.png" alt="" />
          <a href="#">Support</a>
        </li>
        <li>
          <img
            class="header_icons"
            src="../assets/images/envelope.png"
            alt=""
          />
          <a href="#">Contact</a>
        </li>
      </ul>
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
.header {
  display: flex;
  height: 200px;
  width: 70%;
  margin: auto;
  background-color: #fefefe;
}
.logo {
  width: 200px;
}
.nav {
}
ul {
  list-style-type: none;
  display: flex;
  
}
li {
}
a {
  text-decoration: none;
  text-align: center;
  display: block;
}
</style>

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
          <img class="header_icons" src="../assets/images/chat.png" alt="" />
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
  margin: 0 200px;
  display: flex;
  height: 150px;
  align-items: center;
  justify-content: center;
  background-color: #fefefe;
}
.logo {
  width: 200px;
}

ul {
  list-style-type: none;
  display: flex;
  align-self: center;
  text-align: center;
}
li {
  margin: 0 3.5em;
}
li:hover {
  cursor: pointer;
}
.header_icons {
  width: 40px;
}
a {
  text-decoration: none !important;
  color: #56509f !important;
  text-align: center;
  display: block;
}
</style>

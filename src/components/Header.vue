<template>
  <div class="header">
    <nav class="navbar navbar-light">
      <div class="container header_container">
        <a class="navbar-brand" href="#">
          <img
            class="header_icons"
            src="../assets/images/logo.png"
            alt=""
            width="200"
            height=""
          />
        </a>
        <ul class="nav justify-content-center text-center">
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
    </nav>
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
.navbar {
  padding: 0 !important;
}
li.nav-item {
  padding-top: 50px;
  margin: 0 20px;
  height: 142px;
}
li.nav-item:hover {
  background-color: #fd6500;
}

img.header_icons {
  color: #56509f;
  font-weight: 700;
}
a {
  color: #56509f !important;
}

// .header {
//   margin: 0 200px;
//   display: flex;
//   height: 150px;
//   align-items: center;
//   justify-content: center;
//   background-color: #fefefe;
// }
// .logo {
//   width: 200px;
// }

// ul {
//   list-style-type: none;
//   display: flex;
//   align-self: center;
//   text-align: center;
// }
// li {
//   margin: 0 3.5em;
// }
// li:hover {
//   cursor: pointer;
// }
// .header_icons {
//   width: 40px;
// }
// a {
//   text-decoration: none !important;
//   color: #56509f !important;
//   text-align: center;
//   display: block;
// }
</style>

<template>
  <div class="header">
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

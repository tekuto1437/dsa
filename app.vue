<template>
  <div>
    <div class="welcome-section">
      <ContactWelcome/>
      <img src="./assets/svg/svg7.svg" alt="">
    </div>
    <div class="container">
      <img class="first" src="./assets/svg/svg1.svg" alt="">
      <img class="second" src="./assets/svg/svg1.svg" alt="">
      <img class="third" src="./assets/svg/svg1.svg" alt="">
      <Footer></Footer>
    </div>
  </div>
</template>


<style>
* {
    margin: 0;
    padding: 0;
}

html, body {
    background-color: #36363F;
    height: 100%;
    width: 100%;
}

img {
    width: 500px;
    height: 250px;
}

.container {
  position: relative;
  height: 80vh;
}

.first {
  width: 150px;
  height: 150px;
  position: absolute;
  left: 15%;
  top: 35%;
  z-index: 1;
}
.second {
  width: 250px;
  height: 250px;
  position: absolute;
  left: 45%;
  top: 2%;
  z-index: 1;
}

.third {
  width: 200px;
  height: 200px;
  position: absolute;
  left: 75%;
  top: 50%;
  z-index: 1;
}

.welcome-section {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}
</style>
<script>
import ContactWelcome from "./components/contactWelcome";
import UserForm from "./components/userForm";
export default {
  components: {UserForm, ContactWelcome}
}
</script>

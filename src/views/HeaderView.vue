<template>
  <header>
    <section class="sub-header">
      <div class="sub-header-1"><h2>Welcome to Our Store Hiscraves</h2></div>
      <div class="call">
        <p><i class="fa-solid fa-phone"></i></p>
        <p>Call Us: 1234567890</p>
      </div>
    </section>
    <section class="main-header">
      <div><i class="fa-solid fa-bars"></i></div>
      <div>
        <p style="font-family: 'Playfair Display', serif">Logo Here</p>
      </div>
      <div class="icon-container">
        <a><i class="fa-solid fa-magnifying-glass"></i></a>
        <a><i class="fa-solid fa-heart"></i></a>
        <a><i class="fa-solid fa-cart-shopping"></i></a>
        <a><i class="fa-regular fa-user"></i></a>
      </div>
    </section>
  </header>
</template>
  
  <script lang="ts">
import { Component, Vue } from "vue-property-decorator";
//   import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

// @Component({
//   name:'HeaderView',
//   components: {
//   //   HelloWorld,
//   },
// })
export default {};
</script>
  <style lang="scss" scoped>
a {
  cursor: pointer;
}
a:hover {
  // padding-bottom: 5px;
  transform: rotateY(180deg);
}
.sub-header {
  background-color: rgb(13, 13, 13);
  color: white;
  display: flex;
  justify-content: space-between;
  padding: 10px 5vw;
  font-family: 'Montserrat', sans-serif;
  .sub-header-1 {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-left: 10%;
  }
  h2 {
    font-size: 16px;
  }
}
.sub-header .call {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  padding: 5px 2vw;
}
.sub-header .call p {
  margin: 0px 10px;
}
.main-header {
  background-color: white;
  color: "#1F1F1F";
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  text-align: center;
  align-items: center;
  padding: 15px;
}

.main-header .icon-container {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  padding: 10px 5vw;
  color: "#858585";
  fill: "#858585";
}
</style>
  
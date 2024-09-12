<script setup>

</script>

<template>
<div class="header">
  <div class="logo"><img src="https://picsum.photos/150/150" alt=""></div>
  <ul class="navLinks">
    <li><a href="#" class="link">ABOUT</a></li>
    <li><a href="#" class="link">NEWS</a></li>
    <li><a href="#" class="link">STAFF</a></li>
  </ul>
</div>
</template>

<style scoped>
.header{
  position: relative;
  top:0;
  margin: 0;
  width: 100vw;
  height: 80px;
  background-color: rgb(105, 105, 105);
}
.navLinks{
  width: 50%;
  position: absolute;
  bottom: 0;
  right: 0;
  display: flex;
  justify-content: space-evenly;

}
.link{
  font-size: 24px;
  font-weight: bold;
  color: wheat;
}
.logo img{
  width: 150px;
  height: 80px;
  border-radius: 10px;

  position: absolute;
  top: 0;
  left: 15%;
}
</style>
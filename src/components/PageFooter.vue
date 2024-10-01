<script setup>

</script>

<template>
<div class="footer">
  <div class="logo"><img src="https://picsum.photos/200/100" alt=""></div>
  <div class="copyright">NJ © 2024</div>
  <ul class="contacts">
    <li>02-00012345</li>
    <li>123456@gmail.com</li>
    <li>台北市精華街99巷7號</li>
  </ul>
</div>
</template>

<style scoped lang="scss">
.footer{
  position: fixed;
  display: flex;
  justify-content: space-evenly;
  align-content: space-around;
  bottom: 0;
  margin: 0;
  width: 100%;
  height: 80px;
  background-color: rgb(75, 75, 75);
}
.contacts{
  width: 100%;
  color: antiquewhite;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
.contacts li{
  text-align: end;
  margin: 8px 10vw 0 0;
}
.copyright{
  background-color: #fff;
  width: 5vw;
  height: 1em;
}
</style>
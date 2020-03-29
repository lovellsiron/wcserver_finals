<template>
<div>
    <header class="py-5 bg-image-full" style="background-image: url('../assets/header.png');">
    <img class="img-fluid d-block mx-auto" src="../assets/header.png" alt="">
  </header>

  <!-- Content section -->
  <section class="py-5">
    <center><img id="img-top" src="../assets/1.jpg" width="1200px;"></center>
<br><br><br>

  </section>

  <section class="py-5 bg-image-full" style="background-image: url('../assets/2.png');">
  <img class="img-fluid d-block mx-auto" src="../assets/2.png" alt="">
<a href="#" class="button1">SIGN UP</a>

  </section>
</div>

</template>

<script>
export default {
  name: 'home',

}
</script>


<style>
section > .button1 {
  background-color: white;
  border: none;
  color: #d2032d;
  padding: 18px 60px;
  text-align: center;
  letter-spacing: 3px;
  font-weight: bold;
  text-decoration: none;
  display: inline-block;
  font-size: 20px;
  margin: 4px 2px;
  cursor: pointer;
  position: relative;
  top: -140px;
  left: 230px;
}

.button1:hover{
  color: #5c5c5c;
  text-decoration: none;
}
</style>

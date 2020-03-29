<template>
<div>
    <header class="py-5 bg-image-full" style="background-image: url('../assets/header.png');">
    <img class="img-fluid d-block mx-auto" src="../assets/header-news.png" alt="">
  </header>

  <!-- Content section -->
  <section class="py-5">
    <center><img id="img-top" src="../assets/4.jpg" width="1200px;"></center>
<br>

  </section>

  <section class="py-5">
  <p class="content-text">Get up to date with the hottest and latest menu of your one and only instant food<br>
  brand, HaoChi. Through the use of advanced technology, selection of ingredients<br>
  and quality control. HaoChi provides consumers with a "third way to eat" that is<br>
  different from home cooking and restaurant food.<br><br>
  Being both healthy and delicious, it is both convenient and flexible. In packaging<br>
  design, we give priority to how to distinguish it from the existing instant food in<br>
   the market, and cope with hundreds of individual products that may appear in the<br>
  future through systematic design</p>

  </section>

    <section class="py-5 bg-image-full" style="background-image: url('../assets/2.png');">
  <img class="img-fluid d-block mx-auto" src="../assets/5.png" alt="">
<a href="#" class="button">ORDER NOW</a>
</section>
</div>

</template>

<script>
export default {
  name: 'home',

}
</script>


<style>
.content-text{
    text-align: center;
    font-size: 18px;
    letter-spacing: 4px;
}

section > .button {
  background-color: #ce1912;
  border: none;
  color: white;
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
  top:-90px;
  left: 280px;
}

.button:hover{
    text-decoration: none;
    color: #5c5c5c;
}
</style>

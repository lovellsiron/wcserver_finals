<template>
    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <img src="../assets/haochi.png" width="130px"><br><br>
            <p class="text-justify">HaoChi is a Chinese instant food brand. It provides a variety of flavors that allow the consumers to experience their rich tradtion as well as something called "third way to eat" that is different from home cooking and restaurant food. Not only is it both convenient and flexible, the word HaoChi literally translates to delicious. Which describes exactly what our brand is all about, delivering healthy and delicious food.</p>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Categories</h6>
            <ul class="footer-links">
              <li><a href="/">Home</a></li>
              <li><a href="#">Menu</a></li>
              <li><a href="/Members">Members</a></li>
              <li><a href="/News">News</a></li>
              <li><a href="/Events">Events</a></li>
              <li><a href="/Login">Account</a></li>
            </ul>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Links</h6>
            <ul class="footer-links">
              <li><a href="">About Us</a></li>
              <li><a href="#">Contact</a></li>
              <li><a href="#">Email</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Sitemap</a></li>
              <li><a href="#">Phone</a></li>
            </ul>
          </div>
        </div>
        <hr>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">Copyright &copy; 2010 All Rights Reserved by 
         <a href="#">HaoChi</a>.
            </p>
          </div>


        </div>
      </div>
</footer>
</template>

<style>
.site-footer
{
  background-color:#f8f9fa;
  padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:black;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#d2320d;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:#5c5c5c;
}
.site-footer a:hover
{
  color:black;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:#5c5c5c;
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:black;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}



</style>
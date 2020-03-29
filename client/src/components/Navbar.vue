
<template>
<nav class="navbar navbar-icon-top navbar-expand-lg navbar-dark bg-light">

  <a class="navbar-brand" href="#"><img id="icon" src="../assets/haochi.png" width="200px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">

      <li class="nav-item active">
              <a class="nav-link">
        <router-link to="/">
         HOME 
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/Members">
         MEMBERS 
        </router-link>
          </a>
      </li>
      <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/News">
         NEWS  
        </router-link>
          </a>
      </li>
       <li class="nav-item active">
        <a class="nav-link">
        <router-link to="/Events">
         EVENTS
        </router-link>
          </a>
      </li>
      
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-dark my-2 my-sm-0" type="submit">Search</button>
      <form action="/Login">
        <button class="btn btn-outline-dark my-2 my-sm-0 ml-2" type="submit">Log in</button></form>
           <form action="/Signup">
          <button class="btn btn-outline-dark my-2 my-sm-0 ml-2" type="submit">Sign up</button></form>
    </form>
  </div>
</nav>
</template>

<style>

#icon{
padding-right: 10px;
padding-left: 20px;

}

.nav-item a{
  color: #5c5c5c;
  font-size: 18px;
  padding-right: 50px;
  letter-spacing: 2px;
}

.nav-item a:hover{
  text-decoration: none;
 color: black; 
}


</style>

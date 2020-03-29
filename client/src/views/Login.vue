<template>
<div>
    

  <!-- Content section -->
  <section class="py-3">
<form class="login">
        <div class="container">
            <div class="row h-100 justify-content-center align-items-center">
                <div class="col-md-5" id="home">
                    <h2>Log In</h2>
                    <div class="form-group text-center">
                        <label for="username">Username</label>
                        <input type="text" class="form-control" name="username" id="username" placeholder="Username" v-model="username" required autocomplete="off"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="password">Password</label>
                        <input type="password" class="form-control" name="password" id="password" placeholder="Password" v-model="password" required autocomplete="off"/>
                    </div>
                    <div class="form-group text-center">
                        <button class="btn btn-lg btn-danger" type="submit"> Login </button>
                    </div>
                    <h5 style="text-align:center;"><a href="">Forgot your account?</a></h5>
                </div>
            </div>
        </div>
    </form>
  </section>

  
</div>

</template>

<script>

</script>


<style>

h5 > a {
 color:#bc0725;;
}

label{
  
  font-family: 'Century Gothic';
  font-size: 20px;
}
h2{
  color:#bc0725;
  font-family: 'Century Gothic';
  text-align: center;
}


</style>

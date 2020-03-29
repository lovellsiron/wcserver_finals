<template>
<div>
    
  <!-- Content section -->
  <section class="py-5">
    <form class="signup" @submit.prevent = 'register'>
        <div class="container">
            <div class="row h-100 justify-content-center align-items-center">
                <div class="col-md-5">
                    <h2>Create an Account</h2>
                    <div class="form-group text-center">
                        <label for="first_name">First Name</label>
                        <input type="text" class="form-control" name="fname" id="fname" placeholder="First Name" v-model="fname"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="middle_name">Middle Initial</label>
                        <input required autocomplete="off" type="text" class="form-control" name="mname" id="mname" placeholder="Middle Initial" v-model="mname"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="last_name">Last Name</label>
                        <input required autocomplete="off" type="text" class="form-control" name="lname" id="lname" placeholder="Last Name" v-model="lname"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="address">Mobile No.</label>
                        <input required autocomplete="off" type="number" class="form-control" name="mobilenum" id="mobilenum" placeholder="Mobile No." v-model="mobilenum"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="address">Address</label>
                        <textarea required autocomplete="off" type="text" class="form-control" name="address" id="address" placeholder="Address" v-model="address"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="birthdate">Birthdate</label>
                        <input required autocomplete="off" type="text" class="form-control" name="bdate" id="bdate" placeholder="Birthdate" v-model="bdate"/>
                    </div>
                
                    <div class="form-group text-center">
                        <label for="email_address">Email Address</label>
                        <input required autocomplete="off" type="email" class="form-control" name="email" id="email" placeholder="Email Address" v-model="email"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="username">Username</label>
                        <input required autocomplete="off" type="text" class="form-control" name="username" id="username" placeholder="Username" v-model="username"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="password">Password</label>
                        <input pattern="(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{8,}" title="Must contain at least one number and one uppercase and lowercase letter, and at least 8 or more characters" required autocomplete="off" type="password" class="form-control" name="password" id="password" placeholder="Password" v-model="password"/>
                    </div>
                    <div class="form-group text-center">
                        <label for="confirm_password">Confirm Password</label>
                        <input  required autocomplete="off" type="password" class="form-control" name="cpass" id="cpass" placeholder="Confirm Password" v-model="cpass"/>
                    </div>
                    <div class="form-group text-center">
                        <button class="btn btn-lg btn-danger" type="submit"> Register </button>
                        <button class="btn btn-lg btn-danger ml-5" type="button"> Cancel </button>
                    </div>
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

 
</style>

<template >
    <body>    
    <div class="container ">    
  <div class="row custom-row justify-content-center align-items-center no-gutters ">
    <div class="col-md-5 custom-col border d-none d-md-flex">      
         <img class="rounded-sm w-100 h-100 border " src="christelijk.jpg">         
    </div>
    <div class="col-md-7 custom-col border border-dark rounded bg-warning"> 
      <forms>     
      <div class="form-group ml-5 mt-4 w-fluid justify-content-start">
        <img class="rounded-sm custom-img " src="Picture1.png" >  
        <label class="custom-fs display-6 ml-2" >Login Here</label>    
      </div> 
       <forms >
        <div class="form-group m-3 mt-5" >
          <label class="align-content-center font">Email Address</label>
          <input  id="email" type="email" class="form-control align-content-center"  placeholder="Please Input Email" >
        </div>
        <div class="m-3 ">
          <label class="align-content-center">Password</label>
          <input id="password"  type="password"  class="form-control align-content-center"  placeholder="Please input Password">
        </div>
        <div class="container">
          <div class="row g-2 mb-3">
            <div class="col-6">
              <div class="form-check">
                <input class="form-check-input ml=2" type="checkbox">
                <label class="check-label">Remember me</label>
              </div>
            </div>
            <div class="col-6 ">             
              <a href="#" class="" style="float:right" >Forgot Password</a> 
            </div>
          </div>        
        </div>
        <div class="container text-left">
          <div class="row g-2 mb-3">
            <div class="col-6 fs-6" style="width:50px">
              Don't have account?
              <NuxtLink to="/Register"  >Register Here</NuxtLink>
            </div>
            <div class="col-6" >
            <NuxtLink to="/Home" class="btn btn-primary bg-danger border-warning form-control" >Login</NuxtLink>
            </div>  
          </div>          
        </div>        
      </forms>
      </forms>
    </div>
  </div>
</div>
</body>
</template>

<script>
export default {
  name: 'Login',
}
</script>



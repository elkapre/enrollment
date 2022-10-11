<template>
<body class="bg-white">
  <div>
    <div class="mx-auto mt-4" style="width:200px">
      <img class="rounded-sm " src="Picture1.png">       
    </div>        
    <div class="mx-auto border border-dark rounded mt-4 bg-warning" style="width:500px" >    
      <forms >
        <div class="form-group m-3" >
          <label class="align-content-center font">Email Address</label>
          <input  id="email" type="email" class="form-control align-content-center"  placeholder="Please Input Email" >
        </div>
        <div class="m-3">
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
              <a href="#" class=" ">Register Here</a> 
            </div>
            <div class="col-6" >
            <button type="submit" class="btn btn-primary bg-danger border-warning form-control" >Submit</button>
            </div>  
          </div>          
        </div>        
      </forms>
    </div>
  </div>
  </body>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<template>
<body>
    <div>
      <div class="mx-auto mt-4" style="width:200px">
         <img class="rounded-sm " src="Picture1.png">       
      </div>        
    <div class="mx-auto border border-dark rounded mt-4" style="width:500px" >    
      <forms >
        <div class="form-group m-3" >
          <label class="align-content-center">Email Address</label>
          <input  id="email" type="email" class="form-control align-content-center" placeholder="Please Input Email" >
        </div>
        <div class="m-3">
          <label class="align-content-center">Password</label>
          <input id="password"  type="password"  class="form-control align-content-center" placeholder="Please input Password">
          </div>
        <div class="mx-auto" style="width:100px">
          <button type="submit" class="btn btn-primary my-3">Submit</button>
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

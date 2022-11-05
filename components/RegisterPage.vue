<template>
   <div class="container bg-warning p-3 mt-5">
    <h1 class="m-5 ">Registration</h1>
    <div class="form-group m-5">
        <div class="row">
            <div class="col-md-4 ">
               First Name
            </div>
            <div class="col-md-4 ">
               Middle Name
            </div>
            <div class="col-md-4 ">
               Last Name
            </div>
        </div>
        <div class="row ">
            <div class="col-md-4 ">
              <input  id="Fname" type="text" class="form-control align-content-center w-100"  placeholder="" >
            </div>
            <div class="col-md-4 ">
                <input  id="Mname" type="text" class="form-control align-content-center w-100"  placeholder="" >
            </div>
            <div class="col-md-4 ">
                <input  id="Lname" type="text" class="form-control align-content-center w-100"  placeholder="" >
            </div>       
        </div>
        <div class="row mt-5">
           <div class="col-md-4">Date of Birth</div>
           <div class="col-md-8">Address</div>           
        </div>
        <div class="row mt-2">
            <div class="col-md-4"> <input  id="DoB" type="text" class="form-control align-content-center w-100"  placeholder="" ></div>
             <div class="col-md-8"> <input  id="Address" type="text" class="form-control align-content-center w-100"  placeholder="" ></div>              
        </div>           
        <div class="row mt-5">
            <div class="col-md-7">
                <select class="custom-select " > 
                    <option value="" class="text-muted">Select Sex</option>
                    <option value="1">Male</option>
                    <option value="2">Female</option>
                </select>
            </div>
            <div class="col-md-5"><input  id="Address" type="text" class="form-control align-content-center w-100"  placeholder="Nationality" ></div>        
        </div> 
        <div class="row justify-content-center m-5"><NuxtLink to="/Login" class="btn btn-primary bg-danger border-warning form-control w-25" >Submit</NuxtLink></div>  
    </div>       
   </div>
</template>


<script>
export default {
  name: 'RegisterPage',
}
</script>




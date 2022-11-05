<template>
<div>
       <AppHeader />
  <div class="container px-0">
    <br>
    <b-button v-b-modal.modal-1 >Add students</b-button>
      <b-modal id="modal-1" hide-footer title="Add Student">               
        <div class="row mt-5">
            <div class="col-md-8 "><input id="form-name" v-model="item.name"  type="text"  placeholder="Student Name" class="form-control" required></div>
            <div class="col-md-4 "><input v-model="item.desc" type="text" placeholder="Course" class="form-control" @v-on:keyup.enter="addItem" required></div>            
        </div>             
        <div class="modal-footer mt-3">
          <b-button variant="success" class="mt-3" @click="addItem"  >OK</b-button>
        </div>                        
      </b-modal>         
    <table class="table table-striped table-bordered table-sm mt-3">
      <thead class="thead-light">
        <th>Student Name</th>
        <th>BSIT</th>
        <th class="col-2">Edit/Del</th>
      </thead>
      <tr v-for="item in items" :key="item.name">
        <td>
          <input v-if="item.edit"  v-model="item.name" type="text" class="form-control" @v-on:keyup.enter="item.edit = !item.edit" >
          <span v-else>{{item.name}} </span>
        </td>
        <td>
          <input v-if="item.edit"  v-model="item.desc" type="text" @v-on:keyup.enter="item.edit = !item.edit" >
          <span v-else>{{item.desc}} </span>
        </td>
        <td><button class="btn btn-info" @click="item.edit = !item.edit" >Edit</button>
          <button class="btn btn-danger" @click="removeItem(index)" >Remove</button></td>
      </tr>
    </table>
</div>
</div>
</template>

<script scope>
  
  export default {        
    data() {
    return {
      item: {name: "", desc: "", edit: false},
      items: []
    }
  },
  methods:{
    addItem() {
      this.items.push({
        name:this.item.name, desc:this.item.desc, edit: false}
        );
      this.item = [];
        
    },
    removeItem(index){
      this.items.splice(index, 1)
    }
  }
  }
</script>

<style scoped>
.form-inline input {
  margin-right:8px;
}
</style>




<template>
<div>
    <b-button v-b-toggle.sidebar-1 variant="outline-warning"> 
      SideBar
    </b-button>
    <b-sidebar id="sidebar-1" title="Sidebar" shadow>
      <ul class="">
      <li class="nav-item active">
        <NuxtLink to="/Home">Home page</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/About">About</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/Register">Register</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/Login">Login</NuxtLink>
      </li>
    </ul>
    </b-sidebar>
  </div>
</template>


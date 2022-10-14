<template>
<body > 
 <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">School</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div id="navbarSupportedContent" class="collapse navbar-collapse" >
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active mx-3">
        <NuxtLink to="/Home">Home</NuxtLink>
      </li>
      <li class="nav-item mx-3">
      <NuxtLink to="/About">About</NuxtLink>
      </li>      
      <li class="nav-item mx-3">
        <NuxtLink to="/Login">Login</NuxtLink>
      </li>
    </ul>
  </div>
</nav>
</body>
</template>

<script>
export default {
  name: 'AppHeader',
}



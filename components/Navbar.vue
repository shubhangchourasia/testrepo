<template>
    <div>
        <!-- <nuxt-link to='/'>Home</nuxt-link>
        <nuxt-link to='/hr/hr'>HR</nuxt-link> -->
    



  <nav class="navbar navbar-expand-md bg-white navbar-dark">
  <!-- Brand -->
  <nuxt-link to='/' class="nav-link text-dark navbar-brand"><h2>LOGO</h2></nuxt-link>
  <div class="vl"></div>


  <!-- Toggler/collapsibe Button -->
  <button class="navbar-toggler bg-dark" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>

  <!-- Navbar links -->
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <nuxt-link to='/' class="nav-link text-dark" >HOME</nuxt-link>
      </li>
      <li class="nav-item">
        <nuxt-link to='/' class="nav-link text-dark login" >LOGIN</nuxt-link>
      </li>      
      <li class="nav-item">
        <nuxt-link to='/' class="nav-link text-dark" >SIGN UP</nuxt-link>
      </li>
    </ul>
  </div>
</nav>
    </div>
  
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.logo{
    border-right: 5px solid #F1F3F5;
}
.navbar{
    border-bottom: 5px solid #F1F3F5;
    padding-bottom: 0px;
    padding-top: 0px;
}
.login{
  background-color: coral;
  border: coral;
  border-radius: 50px;
  font-size: 20px;
  width: 100px;
  text-align: center;
  color: #F1F3F5;
}
.vl {
  border-left: 2px solid green;
  height: 50px;
}


</style>
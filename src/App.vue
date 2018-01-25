<template>
  <div>
    
     <div class="container">
     <nav>
      <ul class="nav__left">
 
       <li><router-link to="/">Home</router-link></li>
       <li><router-link to="/admin">Admin</router-link></li>
       <li><router-link to='/cart'>Cart</router-link></li>

      </ul>
      </nav>
     </div>
    
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
nav {
  display: block;
  }
</style>

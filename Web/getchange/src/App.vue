<template>
  <div id="app">
    <div id="nav">
  
    </div>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
#app {
font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
background: #E5E5E5 !important;
}


#nav {
 
}

.nav__holder {
font-weight: 500;
font-size: 14px;
line-height: 25px;
font-family: 'Roboto', sans-serif;
letter-spacing: -0.251429px;
color: #013C61;

}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

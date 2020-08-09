<template>
  <div id="app">
    <div id="nav">
  
    </div>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400&display=swap');
:root {
  --main-bg-color: #2BDA53;
  --primary-color: #013C61;
  --main-font:'Roboto', sans-serif;
}
#app {
  font-family: var(--main-font);
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
background: #F6F8F8 ;
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

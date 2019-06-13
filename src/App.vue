<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
    
    html {
        font-size: 1em;
    }
    
    body {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        margin-top: 60px;
        background-color: #000229;
        display: flex;
        justify-content: center;
    }
    
    h1 {font-size: 2.8em; font-weight: 600; margin: 0;}
    h2 {font-size: 2.375em; margin: 0;}
    h3 {font-size: 1.875em; color: #848BFF; margin: 0;}
    h4 {font-size: 1.4em; margin: 0;}
    p {font-size: 1em; color: white; margin: 0;}
    
    nav {
        width: 100%;
    }
    
    
</style>

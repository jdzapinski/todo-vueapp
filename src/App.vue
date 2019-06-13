<template>
    <div id="app">
        <upperNav class="upperNav"></upperNav>
        <todoInput class="todoInput"></todoInput>
    </div>
</template>

<script>
import todoInput from './components/todoInput.vue'
import upperNav from './components/upperNav.vue'

export default {
  name: 'app',
  components: {
    todoInput,
    upperNav
  }
}
</script>

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
    
    
</style>

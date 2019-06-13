<template>
  
    <div class="upperNav">
        <p>Just Another To-do App</p>
    </div>
    
</template>

<script>
export default {
  name: 'upperNav',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    
    p {
        color: #848BFF;
        padding: 0 0 10px 30px;
    }
    
    div.upperNav {
        border-bottom: 2px solid #848BFF;
        width: 100%;
    }

</style>

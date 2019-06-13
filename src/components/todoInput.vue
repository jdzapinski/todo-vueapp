<template>
  
    <form>
        <h3>Add Task</h3>
        <input type="text" placeholder="Add task..." name="add-task">
    </form>
    
    <!--<form @submit.prevent="addSkill">
        <input type="text" placeholder="Enter a skill you have..." v-model="skill" v-validate="'min:5'" name="skill">
        <div class="alert-box">
            <p class="alert-text my-2" v-if="errors.has('skill')">{{ errors.first('skill') }}</p>
        </div>
    </form>-->
    
</template>

<script>
export default {
  name: 'todoInput',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    
    input {
        width: 100%;
        background-color: #27294A;
        border: 1px solid #848BFF;
        padding: 10px;
        font-size: 15px;
        color: #848BFF;
    }
    
    input::placeholder {
        color: #44487C;
    }
    
    input:focus {
        outline: none;
    }
    
    h3 {
        padding-bottom: 5px;
    }
    

</style>

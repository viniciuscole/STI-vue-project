<script>
    let courses = require('../assets/Cursos.js');
    export default{
        name: 'Edit-item',
        data(){
            return{
                courseList: courses,
            }
        }
    }
</script>
<template>
    <span class="create">
        <h2>Edit</h2>
        <form class="form">
            <span class="container-form" id="name">
                <label for="courses">Selecione o Curso:</label>
                <select v-model="courses" required>
                    <option v-for="(course, index) in courseList" :key="index">{{course.name}}</option>
                </select>
                
            </span>
            <input type="submit" id="course-submit" name="course-submit">
        </form>
    </span>
</template>


<style>
    select, option{
        font-family: Helvetica;
        font-size: clamp(.5em, .5em + 1vw, 0.75em);
        border-radius: 3px;
        width: 40%;
        height: 4vh;
    }
</style>
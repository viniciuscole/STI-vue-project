<template>
    <span class="create">
        <h2>Edit</h2>
        <form class="form">
            <span class="container-form" id="name">
                <label for="courses">Selecione o Curso:</label>
                <select name="courses" id="courses">
                    <option value="c1">Curso1</option>
                    <option value="c2">Curso2</option>
                    <option value="c3">Curso3</option>
                    <option value="c4">Curso4</option>
                </select>
            </span>
            <input type="submit" id="course-submit" name="course-submit">
        </form>
    </span>
</template>


<script>
    export default{
        name: 'Edit-item',
    }
</script>
<style>
    select, option{
        font-family: Helvetica;
        font-size: clamp(.5em, .5em + 1vw, 0.75em);
        border-radius: 3px;
        width: 40%;
        height: 4vh;
    }
</style>
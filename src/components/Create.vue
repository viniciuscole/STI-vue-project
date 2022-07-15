<template>
    <span class="create">
        <h2>Create</h2>
        <form class="form">
            <span class="container-form" id="name">
                <label>Nome do Curso:</label>
                <input type="text" id="course-name" name="course-name">
            </span>
            <span class="container-form" id="code">
                <label>Código do Curso:</label>
                <input type="text" id="course-code" name="course-code">
            </span>
            <input type="submit" id="course-submit" name="course-submit">
        </form>
    </span>
</template>


<script>
    export default{
        name: 'Create-item',
    }
</script>
<style>
    .create{
        font-family: Helvetica;
        font-size: clamp(.75em, .75em + 1vw, 1.5em);
    }
    .form{
        
        font-weight: bold;
        color: whitesmoke;
        height: 20vh;
        width: 40vw;
        margin: 1vh 0;
        padding: 3vh;
        background-color: rgba(0, 0, 46, 0.85);
        border-radius: 10px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    .container-form{
        align-items: center;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    #course-name, #course-code{
        border-radius: 3px;
        width: 40%;
        height: 4vh;
    }
    #course-submit{
        border-radius: 3px;
        font-size: 0.75em;
        align-self: center;
        width: 150px;
        height: 4vh;
    }
    input{
        padding: 0 10px;
        font-family: Helvetica;
        font-size: clamp(.5em, .5em + 1vw, 0.75em);
    }
</style>
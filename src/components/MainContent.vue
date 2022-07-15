<template>
    <span class="main">
        <Create/>
        <Edit/>
        <Create/>
        <Create/>
    </span>
</template>
<script>
    import Create from './Create.vue'
    import Edit from './Edit.vue'

    export default{
        name: 'Main-item',
        components:{
            Create,
            Edit
        }
    }
</script>
<style>
    .main{

        height: 80vh;
        margin: 5vw;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        text-align: center;
        flex-wrap: wrap;
    }
</style>
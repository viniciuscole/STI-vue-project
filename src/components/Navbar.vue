<template>
    <span class="navbar">
        <span>
            <img class="logo" src="../assets/logo.png" alt="logo-UFES">
        </span>
        <span>
            Texto2
        </span>
        <span>
            Texto3
        </span>
    </span>
</template>
<script>
    export default{
        name: 'Navbar-item',
    }
</script>
<style>
    *{
        margin: 0;
        padding: 0;
        border: 0;
    }
    .logo{
        height: 60px;
    }
    .navbar{
        display: flex;
        align-items: center;
        color: whitesmoke;
        font-family: Helvetica;
        font-size: 24px;
        background-color: rgba(0, 0, 46, 0.979);
        padding: 10px 30px;
        flex-direction: row;
        justify-content: space-between;
    }

</style>
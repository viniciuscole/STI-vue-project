<template>
    <span class="footer">
        <span class="title">
            Universidade Federal do Espírito Santo
            <span class="sub-title">
                <span>
                    <img class="f-icon" src="../assets/fonte-de-icone-de-marker-gratis.png" alt="icone-localização">
                    Av. Fernando Ferrari, 514 - Goiabeiras, Vitória - ES, 29075-910
                </span>
            </span>
        </span>
        <span class="title">
            Contatos
            <span class="sub-title">
                <span>
                    <img class="f-icon" src="../assets/fonte-de-icone-de-phone-call-gratis.png" alt="icone-localização">
                    (27) 4009-2222
                </span>
                <span>
                    <img class="f-icon" src="../assets/fonte-de-icone-de-facebook-gratis.png" alt="icone-localização">
                    <a href="https://pt-br.facebook.com/ufesoficial/" target="_blank">  facebook.com/ufesoficial</a>
                </span>
                <span>
                    <img class="f-icon" src="../assets/fonte-de-icone-de-youtube-gratis.png" alt="icone-localização">
                    <a href="https://www.youtube.com/ufesoficial" target="_blank">  youtube.com/ufesoficial</a>
                </span>
            </span>
        </span>
    </span>
</template>
<script>
    export default{
        name:'Footer-item'
    }
</script>
<style>
    .footer{
        font-family: Helvetica;
        background-color: rgba(0, 0, 46, 0.979);
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        height: 100px;
        color: whitesmoke;
        align-items: center;
    }
    .title{
        display: block;
        text-align: center;
    }
    a{
        text-decoration: none;
        color: whitesmoke;
    }
    .sub-title{
        text-align: left;
        display: flex;
        flex-direction: column;
    }
    .f-icon{
        height: 15px;
    }
</style>
<template>
    <footer class="bg-dark bg-gradient text-white header-controll">
        <div class="container-fluid py-3">
            <div class="row">
                <div class="col-4">
                    <ul class="nav flex-column">
                        <li class="nav-link"><a href="#">Retornar à Loja</a></li>
                        <li class="nav-link"><a href="#about">Sobre</a></li>
                        <li class="nav-link"><a href="#">Contato</a></li>
                        <li class="nav-link"><a href="#">Suporte</a></li>
                    </ul>
                </div>
                <div class="col-8">
                    <p>
                        Esse projeto tem como finalidade fins didaticos de aprendizagem do criado,
                        não visando quais quer tipo de bonificação ou assinatura.
                        Boas Vendas!!
                    </p>
                    <ul class="nav">
                        <li class="nav-link"><a href="https://www.instagram.com/weslleyvieira.c/"><img src="../assets/img/instagram.png"></a></li>
                        <li class="nav-link"><a href="https://www.linkedin.com/in/weslley-mateus-7a7a43220/"><img src="../assets/img/linkedin.png"></a></li>
                        <li class="nav-link"><a href="https://github.com/TLT-sptb"><img src="../assets/img/github.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
        <p><a href="https://www.flaticon.com/br/icones-gratis/instagram" title="instagram ícones">Créditos Icones</a></p> 
        <div class="text-center" style="background-color: #333; padding: 20px;">
            2022 Copyright: <a href="#">Sales Rocket</a>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'Footer-bar'
}
</script>
<style scoped>
img{
    width: 50px;
}
img:hover{
    color: red;
    box-shadow: rgba(255, 255, 255, 0.5) 0px 3px 8px;
}
</style>

<template>
    <div>
        <div class="container-fluid banner" id="sobre">
            <div class="row mt-5 col-12 mx-0">
                <div class="col-lg-6 wow slideInDown" data-wow-duration="1s" data-wow-delay="1s">
                    <div class="avatar">
                        <img src="../img/jeremias.jpeg" alt="">
                    </div>
                    <div class="social mt-4">
                        <ul>
                            <a href="#"><i class="fab fa-facebook"></i></a>
                            <a href="#"><i class="fab fa-linkedin"></i></a>
                            <a href="#"><i class="fab fa-github"></i></a>
                        </ul>
                    </div>
                </div>
                <div class="col-lg-6 wow slideInLeft" data-wow-delay="0.7s" data-wow-duration="0.7s">
                    <div class="card" id="card">
                        <div class="card-body">
                            <div class="text-avatar">
                                <h1>SOBRE MIM</h1>
                                
                                
                                <p style="text-align: left!important;">
                                    Olá sou Jeremias, Programador com mais de 5 anos de
                                    experiência em projetos complexos e inovadores, atuando
                                    principalmente nas áreas de desenvolvimento web e mobile.
                                    Ao longo da minha carreira, participei em desenvolvimento 
                                    de plataformas escaláveis para e-commerce, apps e sistemas
                                        corporativos.
                                        Tenho forte expertise em arquitetar soluções robustas, desde
                                        a concepção até a implementação, sempre focado na qualidade
                                        do código, automação de testes e práticas de DevOps. Além disso,
                                        sou apaixonado por aprender novas tecnologias e estou sempre 
                                        buscando formas de otimizar o desempenho de aplicações e resolver
                                            desafios técnicos complexos. 
                                            Meu objetivo é continuar aprimorando minhas habilidades e colaborar
                                            com empresas que desejam transformar suas operações por meio da tecnologia.

                                </p>
                                <hr>
                                <!--<div class="d-flex">
                                    <p class="mr-1">Idade: </p>
                                    <p> {{ idade }}</p>
                                </div>-->
                                <div class="d-flex">
                                    <p class="mr-1" >Endereço: </p>
                                    <p>{{ endereco }}</p>
                                </div>
                                <div class="d-flex">
                                    <p class="mr-1">Freelancer: </p>
                                    <p> Disponível</p>
                                </div>
                                <div class="btn mt-3 btn-lg container">
                                    Download CV <i class="fa fa-file"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    var data = new Date();
    var ano = data.getFullYear();
    var nasc = 2005;
    var calc_idade = ano - nasc; 
    export default{
        name:"sobre",
        data() {
            return {
                idade: calc_idade,
                endereco: "Lubango, Huíla, Angola",
            }
        },
    }
</script>
<style scoped>
    .banner{
       margin-top: 100px;
    }

    .avatar{
        position: relative;
        width: 450px;
        height: 450px;
        display: block;
        margin: 0 auto;
        border: 6px solid lightgreen;
        border-radius: 50%;
        box-shadow: 0 0px 60px 0px lightgreen;
    }

    .avatar img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: 1px 0.4px;
        border-radius: 50%;
    } 

    .text-avatar h1{
        color: lightgreen;
        text-align: center;
        font-size: 20pt;
        margin-top: 10px;
        margin-bottom: 10px;
    }

    .text-avatar h3{
        font-weight: bold;
    }

    .text-avatar hr{
        color: grey;
    }

    .text-avatar hr{
        color: grey;
    }

    .btn{
        background-color: lightgreen;
        color: var(--dark);
        transition: all 0.7s;
    }

    .btn i{
        margin-left: 10px;
    }

    .btn:hover{
        transition: all 0.7s;
        background-color: var(--dark);
        color: lightgreen;
        border: 1px solid lightgreen;
    }

    .social i{
        margin: 10px;
        font-size: 20pt;
    }

    .social{
        display: flex;
        justify-content: center;
    }

    .social a{
        transition: all 0.7;
    }
    .social a:hover{
        transition: all 0.7;
        color: lightgreen;
    }

    #card{
        margin: 0!important;
    }

    @media(max-width: 991px) {
        .avatar{
            width: 300px;
            height: 300px;
            background-color: #fff;
        }

        .text-avatar h1{
            color: lightgreen;
            font-size: 20pt;
        }
    }
</style>


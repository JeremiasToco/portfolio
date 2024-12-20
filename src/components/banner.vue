<template>
    <div class="container-fluid banner">
        <div class="row mt-5 col-12 mx-0">
            <div class="col-lg-6 wow slideInLeft" data-wow-duration="1s" data-wow-delay="1s">
                <div class="text-avatar">
                    <h1>FULLSTACK DEVELOPER</h1>
                    <div class="traco"></div>
                    <h3 class="mb-5">Jeremias Toco</h3>
                    <p>
                        Desenvolvedor fullstack é um profissional de tecnologia
                         que tem habilidades para trabalhar tanto no front-end 
                         (a interface do usuário) quanto no back-end (a lógica do 
                         servidor e o gerenciamento de dados) de uma aplicação. Esse
                          tipo de desenvolvedor é capaz de lidar com todas as etapas de 
                          desenvolvimento de um projeto de software. Essa versatilidade permite 
                          que ele desenvolva soluções completas, desde a interface do usuário até 
                          a integração com bancos de dados e serviços.
                    </p>
                    <div class="social mt-4">
                        <ul>
                            <a href="#"><i class="fab fa-facebook"></i></a>
                            <a href="#"><i class="fab fa-linkedin"></i></a>
                            <a href="#"><i class="fab fa-github"></i></a>
                        </ul>
                    </div>
                    <a href="#contact" class="btn mb-5"><i class="fa fa-phone"></i> Contactar</a>
                </div>
            </div>
            <div class="col-lg-6 wow bounceInDown" data-wow-delay="1.2s" data-wow-duration="1s">
                <div class="avatar">
                    <img src="../img/rb_3957.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default{
        name: "Banner",
    }
</script>
<style scoped>
    .banner{
       margin-top: 100px;
       margin-bottom: 180px;
    }

    .avatar{
        position: relative;
        width: 450px;
        height: 450px;
        display: block;
        margin: 0 auto;
        /*border: 6px solid lightgreen;*/
        border-radius: 50%;
        /*box-shadow: 0 0px 60px 0px lightgreen;*/
    }

    .avatar img{
        width: 100%;
        height: 100%;
        object-fit: cover;
        object-position: 1px 0.4px;
        /*border-radius: 50%;*/
    } 

    .text-avatar h1{
        color: lightgreen;
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
        background-color: #90ee90;
        color: var(--dark);
        transition: all 0.7s;

    }

    .btn i{
        margin-right: 5px;
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
        margin-left: -50px;
        display: flex;
        justify-content: flex-start;
    }

    .social a{
        transition: all 0.7;
    }
    .social a:hover{
        transition: all 0.7;
        color: lightgreen;
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
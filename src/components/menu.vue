<template>
    <div id="menu">
        <div class="avatar">
            <img src="../img/avatar2.jpeg" alt="">
            <h3>Jeremias Toco</h3>
        </div>
        <div class="social mx-0">
            <ul>
                <li><i class="fab fa-facebook"></i></li>
                <li><i class="fab fa-linkedin"></i></li>
                <li><i class="fab fa-github"></i></li>
            </ul>
        </div>
        <hr>
        <ul class="navbar-nav mt-5">
            <li class="nav-item"><a class="nav-link" href="#">Início</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Sobre</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Serviços</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Resumo</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Portfolio</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Contactos</a></li>
        </ul>
    </div>
</template>
<script>
    export default{
       name: 'Menu', 
    }
</script>
<style scoped>
    #menu{
        display: block;
        left: 0;
        background: rgb(2,0,36);

        width: 250px;
        height: 100vh;
    }

    .avatar img{
        width: 150px;
        height: 150px;
        display: block;
        margin: 20px auto;
        border-radius: 50%;
        border: 6px solid #fff;
    }

    .avatar h3{
        color: #fff;
        text-align: center;
        margin: 10px;
        font-size: 18pt;
        font-weight: bold;
    }

    .avatar hr{
        color: grey;
    }

    .navbar-nav a{
        color: #fff;
        font-size: 12pt;
        text-align: center;
        transition: 1s;
    }

    .navbar-nav a:hover{
        color: #007bff;
        transition: 1s;
    }

    .social li{
        list-style: none;
    }

    .social ul{
        display: flex;
    }
    .social i{
        color: #fff;
        margin: 10px;
        font-size: 18pt;
        transition: 1s;
        cursor: pointer;
    }

    .social{
        display: flex;
    }

    .social i:hover{
        transition: 1s;
        color: #007bff;
    }
</style>
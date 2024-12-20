<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-dark">
            <div class="navbar-brands"> 
                <div class="d-flex icons-menu">
                    <img class="logo" src="../img/logo/logo.png" alt="">
                </div>
            </div>
            <buttom class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbar">
                <i class="fa fa-bars"></i>
            </buttom>
            <div class="collapse navbar-collapse" id="navbar">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item active"><a class="nav-link" href="#sobre">Sobre</a></li>
                    <li class="nav-item"><a class="nav-link" href="#tools">Habilidades</a></li>
                    <li class="nav-item"><a class="nav-link" href="#servico">Serviços</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contactos</a></li>
                </ul>
            </div>
        </nav>
    </div>
</template>
<script>
    export default{
        name: "Navbar"
    }
</script>
<style scoped>
    .navbar{
        padding: 20px;
        /*box-shadow: 0 0px 40px -4px lightgreen;*/
    }
    .navbar a{
        color: grey;
        margin: 10px;
    }

    .navbar a:hover{
        color: lightgreen;
    }

    .navbar a:focus{
        color: lightgreen;
    }

    .icon-avatar{
        position: relative;
        width: 50px;
        height: 50px;
        display: block;
        margin: 0 auto;
        border: 2px solid lightgreen;
        border-radius: 50%;
        box-shadow: 0 0px 20px 0px lightgreen;
    }

    .icon-avatar img{
        width: 100%;
        height: 100%;
    }

    .icons-menu{
        align-items: center;
    }

    @media(max-width: 991px) {
        .navbar li{
            border-bottom: 1px solid grey;
        }
        
        .logo{
            width: 220px;
        }
    }

</style>
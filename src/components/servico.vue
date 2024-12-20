<template>
    <div id="servico">
        <div class="col-12 mx-0">
            <div class="text-avatar content">
                <div>
                    <h1 class="text-center mb-5 wow slideInRight" data-wow-delay="1s" data-wow-duration="1s">Meus Serviços</h1>
                </div>
            </div>
        </div>
        <div class="row col-12 mt-5 mx-0">
            <div class="col-lg-4 wow bounceInUp" data-wow-delay="1s" data-wow-duration="1s">
                <div class="card" id="card">
                    <img src="../img/dev-web.jpg" alt="">
                    <div class="card-body">
                        <h4>Criação de WebSites</h4>
                        <p>
                            Website (ou site) é um conjunto de páginas web interconectadas 
                            e acessíveis por meio de um navegador da internet.Essas páginas 
                            estão hospedadas em um servidor e podem conter textos, imagens, 
                            vídeos, links, formulários e outros conteúdos interativos.</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 wow bounceInUp" data-wow-delay="1s" data-wow-duration="1.5s">
                <div class="card" id="card">
                    <img src="../img/dev-mobile.jpg" alt="">
                    <div class="card-body">
                        <h4>Criação de Aplicativos móveis</h4>
                        <p>
                            Aplicativo móvel (ou app) é um software desenvolvido para ser executado em dispositivos
                             móveis, como smartphones, tablets e smartwatches. Os aplicativos móveis oferecem uma ampla 
                             gama de funcionalidades.
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 wow bounceInUp" data-wow-delay="1s" data-wow-duration="2s">
                <div class="card" id="card">
                    <img src="../img/dev-desktop.jpg" alt="">
                    <div class="card-body">
                        <h4>Criação de Aplicativos Desktop</h4>
                        <p>
                            Aplicativos desktop são softwares desenvolvidos para serem executados em 
                            computadores pessoais, como desktops e laptops, geralmente operando nos 
                            sistemas operacionais mais populares, como Windows, macOS e Linux.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: "servico"
}
</script>

<style scoped>
    #servico{
        margin-top: 150px;
    }

    .content{
        /*display: flex;
        justify-content: center;*/
    }

    #card img{
        height: 220px;
        object-fit: cover;
        border-top-left-radius: 10px;
        border-top-right-radius: 10px;
    }

    #card{
        border-top: 0;
        border-bottom: 5px solid lightgreen;
    }
</style>
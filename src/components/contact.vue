<template>
    <div id="contact">
        <div class="text-avatar content">
            <div class="mt-5">
                <h1 class="text-center mb-5 wow slideInRight" data-wow-duration="1s" data-wow-delay="1s">Entre em contacto</h1>
            </div>
        </div>
        <div class="row col-12 mx-0">
            <div class="col-lg-4 wow bounceInLeft " data-wow-delay="1s" data-wow-duration="1s">
                <div class="card" id="card">
                    <div class="card-body">
                       <div class="icon-contact">
                        <i class="fa-solid fa-location-dot fa-3x"></i>
                        <h4 class="mt-4">Minha localização</h4>
                        <p>Lubango, Huíla, Angola</p>
                       </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 wow bounceInLeft " data-wow-delay="1s" data-wow-duration="1.5s">
                <div class="card" id="card">
                    <div class="card-body">
                       <div class="icon-contact">
                        <i class="fa-solid fa-phone fa-3x"></i>
                        <h4 class="mt-4">Contactos</h4>
                        <p>947 277 644 / 958 899 365</p>
                       </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-4 wow bounceInLeft " data-wow-delay="1s" data-wow-duration="2s">
                <div class="card" id="card">
                    <div class="card-body">
                       <div class="icon-contact">
                        <i class="fa-solid fa-location-dot fa-3x"></i>
                        <h4 class="mt-4">E-mail</h4>
                        <p>Jeremiastoco2010@gmail.com</p>
                       </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name:"contact"
}
</script>
<style scoped>
    #contact{
        margin-top: 120px;
        margin-bottom: 100px;
    }
    .icon-contact {
        text-align: center;
        align-items: center;
        padding: 20px;
    }
</style>

<template>
    <div class="content">
        <div class="image-container">
            <img src="../../img/components/tittle-landscape.png" class="tittle-landscape" alt="Imagen de fondo">
            <h1>Encuentra la Propiedad de tus Sueños</h1>
        </div>

        <div class="type-icons">
            <h1>¿Que ofrecemos?</h1>
            <div class="icons-container">
                <div class="icon icon1">
                    <i class="fa-solid fa-house"></i>
                    Casa
                </div>
                <div class="icon icon2">
                    <i class="fa-brands fa-pagelines"></i>
                    Terreno
                </div>
                <div class="icon icon3">
                    <i class="fa-solid fa-building"></i>
                    Departamento
                </div>
            </div>
        </div>

        <div class="recent">
            <h1>Agregado Recientemente</h1>
            <div class="cards-container">
                <div class="card">
                    <img src="../../img/components/tittle-landscape.png" alt="Imagen de título" class="card-image">
                    <div class="card-content">
                        <h2 class="card-title">Propiedad</h2> 
                        <p class="description-card">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p> 
                        <p class="price">$500,000 MXN</p> 
                    </div>
                </div>
                <!-- Aquí puedes añadir más tarjetas -->
                <div class="card">
                    <img src="../../img/components/tittle-landscape.png" alt="Imagen de título" class="card-image">
                    <div class="card-content">
                        <h2 class="card-title">Propiedad 2</h2> 
                        <p class="description-card">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p> 
                        <p class="price">$600,000 MXN</p> 
                    </div>
                </div>
                <div class="card">
                    <img src="../../img/components/tittle-landscape.png" alt="Imagen de título" class="card-image">
                    <div class="card-content">
                        <h2 class="card-title">Propiedad 3</h2> 
                        <p class="description-card">Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p> 
                        <p class="price">$700,000 MXN</p> 
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../scss/home.scss' as *;
</style>

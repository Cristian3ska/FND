<template>
    <header>
        <img src="../../img/icons/fnd_w.png" alt="FND Logo" class="logo">

        <!-- Navegación principal (para pantallas grandes) -->
        <nav class="nav-links">
            <a href="#home">Inicio</a>
            <a href="#propiedades">Propiedades</a>
            <a href="#about">¿Quienes Somos?</a>
            <a href="#buyrosell">Comprar o Vender</a>
            <a href="#contacto">Contacto</a>
        </nav>

        <!-- Botón de menú hamburguesa (para pantallas móviles) -->
        <div class="hamburger-menu" @click="toggleMenu">☰</div>

        <!-- Superposición de fondo -->
        <div class="overlay" :class="{ active: isMenuOpen }" @click="closeMenu"></div>

        <!-- Menú lateral (para pantallas móviles) -->
        <aside :class="['side-menu', { active: isMenuOpen }]">
            <button class="close-menu" @click="closeMenu">✕</button>
            <a href="#home" @click="closeMenu">Inicio</a>
            <a href="#properties" @click="closeMenu">Propiedades</a>
            <a href="#about" @click="closeMenu">¿Quienes Somos?</a>
            <a href="#buyorsell" @click="closeMenu">Comprar o Vender</a>
            <a href="#contact" @click="closeMenu">Contacto</a>
        </aside>
    </header>
</template>

<script>
export default {
    data() {
        return {
            isMenuOpen: false
        };
    },
    methods: {
        toggleMenu() {
            this.isMenuOpen = !this.isMenuOpen;
        },
        closeMenu() {
            this.isMenuOpen = false;
        }
    }
};
</script>

<style lang="scss" scoped>
@use '../../scss/header.scss' as *;
</style>

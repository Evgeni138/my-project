<template>
    <section class="header center">
        <div class="header__logo">
        <img class="header__img" src="@/assets/images/img_heading/Logo.png" alt="Logo" />
        <h3 class="header__interno">Interno</h3>
        </div>
        <div class="header__menu">
        <a href="" class="header__link">Home</a>
        <a href="" class="header__link">Project</a>
        <a href="" class="header__link">Blog</a>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'Heading',

        data() {
        return {
            
        }
    },
    };
</script>

<style scoped lang="scss">
    @import '@/assets/styles/heading.scss';
    @import "@/assets/fonts/fonts.css";
</style>
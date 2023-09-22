<script>
import "../assets/scss/style.scss"

export default {
    name: 'AppNavbar',
    data() {
        return {
            items: [
                {
                    message:'CHARACTERS',
                    active: false
                },
                {
                    message:'COMICS',
                    active: true
                },
                {
                    message:'MOVIES',
                    active: false
                },
                {
                    message:'TV',
                    active: false
                },
                {
                    message:'GAMES',
                    active: false
                },
                {
                    message:'COLLECTIBLES',
                    active: false
                },
                {
                    message:'VIDEOS',
                    active: false
                },
                {
                    message:'FANS',
                    active: false
                },
                {
                    message:'NEWS',
                    active: false
                },
                {
                    message:'SHOP',
                    active: false
                }
            ]
        }
    }
}
</script>


<template>

    <nav>

        <div class="container d-flex justify-between">

            <div class="container-logo">

                <img src="../assets/img/dc-logo.png" alt="">    

            </div>

            <div class="container-menu">
                <a v-for="item in items" href="#">
                    <span id="active" class="color-blu" v-if="item.active">{{ item.message }}</span>
                    <span class="color-black" v-else>{{ item.message }}</span>
                </a>
            </div>

        </div>

    </nav>

</template>

<style>

</style>

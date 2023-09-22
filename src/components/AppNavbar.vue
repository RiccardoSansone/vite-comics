<script>
import "../assets/scss/style.scss"

export default {
    name: 'AppNavbar',
    data() {
        return {
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
                <a href="#">CHARACTERS</a>
                <a href="#">COMIMCS</a>
                <a href="#">MOVIES</a>
                <a href="#">TV</a>
                <a href="#">GAMES</a>
                <a href="#">COLLECTIBLES</a>
                <a href="#">VIDEOS</a>
                <a href="#">FANS</a>
                <a href="#">NEWS</a>
                <a href="#">SHOP</a>
            </div>

        </div>

    </nav>

</template>

<style>

</style>

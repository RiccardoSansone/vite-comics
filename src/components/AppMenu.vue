<script>
import "../assets/scss/style.scss"

export default {
    name: 'AppMenu',
    data() {
        return {
            actions: [
                {
                    name: 'DIGITAL COMICS',
                    img: 'buy-comics-digital-comics.png'
                },
                {
                    name: 'DC MERCHANDISE',
                    img: 'buy-comics-merchandise.png'
                },
                {
                    name: 'SUBSCRIPTION',
                    img: 'buy-comics-subscriptions.png'
                },
                {
                    name: 'COMIC SHOP LOCATION',
                    img: 'buy-comics-shop-locator.png'
                },
                {
                    name: 'DC POWER VISA',
                    img: 'buy-dc-power-visa.svg'
                }
            ]
        }
    },
    methods: {
        getImagePath: function(img) {
            return new URL(`../assets/img/${img}`, import.meta.url).href; 
        }
    }
}
</script>


<template>
    <div class="bg-blu">
        <div id="menu" class="container d-flex justify-around">
            <div v-for="action in actions" class="d-flex align-center gap-1">
                <img :src="getImagePath(action.img)" alt="">
                <div>{{ action.name }}</div>
            </div>
        </div>
    </div>
</template>

<style>

</style>

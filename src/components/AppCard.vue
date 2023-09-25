<script>
import "../assets/scss/style.scss"

export default {
    name: 'AppCard',
    data() {
        return {
            
        }
    },
    props: {
        comic: String
    }
}
</script>


<template>

    <img :src="comic.thumb" alt="">
    <small>{{ comic.series }}</small>

</template>

<style>

</style>

<template>
    <div class="box-cards">

        <div class="card" v-for="(card, index) in cards" :key="index">
            <a href="#">
            <div class="img-card">
                
                <img :src="card.thumb">
                
            </div>

            <div class="text">
                <span>{{card.series}}</span>
            </div>
            </a>
        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style>

@import "../assets/style/common.scss";


</style>
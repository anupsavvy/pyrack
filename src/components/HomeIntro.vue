<template>
    <v-container fluid fill-height class="home-intro" style="max-height:100vh;">
        <v-layout justify-center align-center column pa-5>
            <v-img :src="require('../assets/fulllogoshort.png')" contain class="img"></v-img>
            <v-btn fab class="mt-1 white darken-4">
                <v-icon large color="#aa0247">expand_more</v-icon>
            </v-btn>
        </v-layout>
    </v-container>
</template>
<script>
export default {
}
</script>
<style scoped>
   .home-intro{
        background-color:#aa0247;
        background-size: cover;
        width: 100%;
        height: 100%;
   }
   .img{
       height: 50%;
       width:50%;
   }
</style>

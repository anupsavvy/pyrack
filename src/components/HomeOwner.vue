<template>
    <v-container fluid id="owner">
        <v-layout justify-center align-center column>
            <v-flex class="display-2 text-xs-center my-5">Experience</v-flex>
            <v-flex>
                <v-avatar class="mt-3" size="100px">
                    <v-img :src="require('../assets/anup.jpeg')"></v-img>
                </v-avatar>
            </v-flex>
        </v-layout>
        <v-layout row justify-center>
            <v-flex md8>
                <p class="subheading pa-3 text-xs-center">The man behind Pyrack is Anup Sawant.
                     He has worked across corporate and academic setups for over 10 years.
                      He has served as the lead on various research software projects that work on graph theories, machine learning and information retrieval platform.
                       With the amount of experience he has working on web platforms, he aims to help his clients in developing smart web applications that leverage rich data in order to enhance user experience.</p>
                <p class="subheading pa-3 text-xs-center">Get in touch to know how you can benefit from intelligent applications : <strong>anup@pyrack.com</strong></p>
            </v-flex>
        </v-layout>
    </v-container>
</template>
<style scoped>
    #owner{
        background-color: #f5f5f5;
    }
    #divider{
        color: #aa0247;
    }
</style>


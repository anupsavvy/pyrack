<template>
    <v-container grid-list-lg id="summary">
        <v-layout column>
            <v-flex class="display-2 text-xs-center my-5">Intelligent Applications</v-flex>
            <v-flex>
                <div class="headline mt-3">Why Python?</div>
                <p class="subheading mt-3">Python is a general-purpose language, which means it can be used to build just about anything, which will be made easy with the right tools/libraries. Professionally, Python is great for backend web development, data analysis, artificial intelligence, and scientific computing. Many developers have also used Python to build productivity tools, games, and desktop apps, so there are plenty of resources to help you learn how to do those as well.</p>
            </v-flex>
            <v-flex>
                <div class="headline mt-3">What are intelligent applications?</div>
                <p class="subheading mt-3">Intelligent applications are the applications which makes the use of  machine learning technology to create apps that use historical and real-time data to make predictions and decisions to deliver rich, adaptive, personalized experiences for users.These apps combine predictive and prescriptive analytics, customer data, product insights, and operational vision with contemporary user-focused design and application development tools to create a highly impact-full experience for their users.</p>
                <p class="subheading mt-3">The intelligent apps can leverage data, algorithms, cutting-edge technologies, and have a continuous learning approach and improves the interactions of people and machines by anticipating the actions. These apps are able to learn the behavioral, contextual and emotional patterns of a user in real time and provides a personalized experience in every successive session.</p>
            </v-flex>
            <v-flex>
                <div class="headline mt-3">Tools and Frameworks</div>
            </v-flex>
        </v-layout>
        <v-layout row wrap>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/django.png')" contain height="50"></v-img>       
            </v-flex>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/djangorest.png')" contain height="50"></v-img>        
            </v-flex>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/pytorch.png')" contain height="50"></v-img>        
            </v-flex>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/tf.png')" contain height="50"></v-img>         
            </v-flex>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/scikit.svg')" contain height="50"></v-img>        
            </v-flex>
            <v-flex xs6 sm6 md4 pa-5>
                <v-img :src="require('../assets/vuejs.png')" contain height="50"></v-img>         
            </v-flex>
        </v-layout>
    </v-container>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    #summary{
        background-color: white;
    }
</style>

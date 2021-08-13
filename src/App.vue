<template>
 <v-app>
   <v-content id="content">
     <router-view/>
   </v-content>
 </v-app>
</template>

<script>
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Comfortaa:wght@300&display=swap');
  #content{
      background-color: white;
      height:100vh;
  }
</style>

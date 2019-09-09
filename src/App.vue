<template>
  <v-app>
    <v-navigation-drawer app v-model="drawer" dark disable-resize-watcher style="background-color:rgba(170,2,71,0.8);">
            <v-list>
                <template v-for="(item, index) in items">
                    <v-list-tile :key="index">
                        <v-list-tile-content>
                            {{item.title}}
                        </v-list-tile-content>
                    </v-list-tile>
                    <v-divider :key="`divider-${index}`"></v-divider>
                </template>
            </v-list>
    </v-navigation-drawer>
    <v-toolbar app color="#ffffff">
      <v-toolbar-side-icon class="hidden-md-and-up" @click="drawer = !drawer"></v-toolbar-side-icon>
      <v-spacer class="hidden-md-and-up"></v-spacer>
      <v-toolbar-title class="headline text-uppercase">
        <span>PYRACK</span>
      </v-toolbar-title>
      <v-spacer class="hidden-sm-and-down"></v-spacer>
      <v-btn class="hidden-md-and-down" flat href="#summary">Intelligent Applications</v-btn>
      <v-btn class="hidden-md-and-down" flat href="#experience">Experience</v-btn>
      <!-- <v-btn class="hidden-md-and-down" flat>Testimonials</v-btn>
      <v-btn class="hidden-md-and-down" flat>Contact</v-btn> -->
    </v-toolbar>
    <v-content>
      <home></home>
    </v-content>
  </v-app>
</template>

<script>
import Home from '@/views/Home.vue';
export default{
  name: 'App',
  components: {
    Home
  },
  data() {
        return {
            drawer: false,
            items: [
                { title: 'Intelligent Applications' },
                { title: 'Experience' },
                { title: 'Testimonials' },
                { title: 'Contact'}
            ]
        };
    }
}
</script>

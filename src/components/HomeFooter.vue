<template>
  <v-footer
    height="auto"
    id="footer"
  >
    <v-layout
      justify-center
      row
      wrap
    >
      <!-- <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        flat
        round
      >
        {{ link }}
      </v-btn> -->
      <v-flex
        py-3
        text-xs-center
        white--text
        xs12
        id="bfooter"
      >
        &copy;2019 — <strong>Pyrack</strong>
      </v-flex>
    </v-layout>
  </v-footer>
</template>
<script>
  export default {
    data: () => ({
      links: [
        'Home',
        'Services',
        'Blog',
        'Contact Us'
      ]
    })
  }
</script>

<style scoped>
    #footer{
        background-color:#aa0247;
    }
</style>

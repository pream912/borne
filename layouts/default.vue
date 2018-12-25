<template>
  <v-app>
    <template>
      <v-toolbar color="white" app fixed>
         <v-img src="/images/logo.jpg" contain max-height="60px" max-width="120px"></v-img> 
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn flat><span class="caption">About us</span></v-btn>
          <v-btn flat><span class="caption">Products</span></v-btn>
          <v-btn flat><span class="caption">Services</span></v-btn>
          <v-btn flat><span class="caption">Contact us</span></v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </template>
    <v-content>
      <nuxt/>
    </v-content>
      <v-footer
      dark
      height="auto"
      >
      <v-card
        class="flex"
        flat
        tile
      >
        <v-card-title class="green">
          <strong class="subheading">Get connected with us on social networks!</strong>

          <v-spacer></v-spacer>

          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-3"
            dark
            icon
          >
            <v-icon size="24px">{{ icon }}</v-icon>
          </v-btn>
        </v-card-title>

        <v-card-actions class="grey darken-3 justify-center">
          &copy;2018 — <strong>Vuetify</strong>
        </v-card-actions>
      </v-card>
    </v-footer>
  </v-app>
</template>

<script>
  export default {
    head () {
    return {
      script: [
        { src: 'https://cdnjs.cloudflare.com/ajax/libs/rellax/1.7.1/rellax.min.js' }
      ],
    }
    },
    data() {
      return {
        icons: [
        'fas fa-facebook',
        'fas fa-twitter',
        'fas fa-google-plus',
        'fas fa-linkedin',
        'fab fa-instagram'
      ]
      }
    },

  }
</script>

<style>

</style>


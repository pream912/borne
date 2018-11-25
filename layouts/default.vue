<template>
  <v-app>
    <template>
      <v-toolbar color="white" app fixed>
         <v-img src="http://borne.askgee.net/images/logo/logo.jpg" contain max-height="60px" max-width="120px"></v-img> 
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn flat><span class="font-weight-bold">About us</span></v-btn>
          <v-btn flat><span class="font-weight-bold">Products</span></v-btn>
          <v-btn flat><span class="font-weight-bold">Services</span></v-btn>
          <v-btn flat><span class="font-weight-bold">Contact us</span></v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </template>
    <v-content>
      <template>
      <v-layout>
        <div id="mood">
            <img src="~/assets/svg/sky.svg" style="position:absolute; z-index:0; width:100%;" class="rellax" data-rellax-speed="-3" />
            <img src="~/assets/svg/bg.svg" style="position:absolute; z-index:1; bottom: 25%; width:100%" class="rellax" data-rellax-speed="1" />
            <img src="~/assets/svg/mg.svg" style="position:absolute; z-index:2; bottom: 5%; width:100%" class="rellax" data-rellax-speed="5" />
            <img src="~/assets/svg/fg.svg" style="position:absolute; z-index:3; top: 15%; width:100%" class="rellax" data-rellax-speed="7" />
        </div>
        <div id="mood-text">
            <h2 class="display-2 red--text--{lighten}-{4}" style="padding-left: 5px; padding-bottom: 10px"> Best Industrial Service Provider </h2>
            <h1 class="display-4 black--text font-weight-bold"> <span class="red--text"> Borne </span> Technologies </h1>
            <p class="headline black--text" style="padding-left: 8px; padding-top: 15px; padding-bottom: 15px; line-height: 80%"> We provides always our best industrial solution for our clients and  always try to achieve <br> our client's trust and satisfaction.</p> 
            <v-btn round large color="blue"> <span class="white--text font-weight-bold"> Our Services </span> </v-btn>
            <v-btn round large color="green"> <span class="white--text font-weight-bold"> Conatct us </span> </v-btn>
        </div>
      </v-layout>
      </template>

    </v-content>
  </v-app>
</template>

<script>
  import rellax from 'rellax'
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
        
      }
    },

    mounted () {
      var rellax = new Rellax('.rellax');
    }
  }
</script>

<style>
  #mood {
    opacity: .3
  }
  #mood-text {
    margin-left: 15%;
    margin-top: 12%;
    z-index:4
  }
</style>


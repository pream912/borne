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
      <template>
        <v-parallax
        dark
        class="elevation-1"
        src="/images/parallax.jpg">
          <v-layout
          align-center
          justify-center
          column
>
            <v-flex>
              <h2 class="display-2" style="padding-left: 5px; margin-top: 100px"> Best Industrial Service Provider </h2>
              <h1 class="display-4 white--text font-weight-bold"> <span class="red--text text--lighten-1"> Borne </span> Technologies </h1>
              <p class="title white--text" style="padding-left: 8px; line-height: 80%; margin-top: 10px"> We provides always our best industrial solution for our clients and  always try to achieve <br> our client's trust and satisfaction.</p> 
              <v-btn round large color="blue"> <span class="white--text font-weight-bold"> Our Services </span> </v-btn>
              <v-btn round large color="green"> <span class="white--text font-weight-bold"> Conatct us </span> </v-btn>
            </v-flex>
          </v-layout>
        </v-parallax>
      </template>
      <template>
        <section>
          <v-layout
            column
            wrap
            class="my-5"
            align-center
          >

            <v-flex xs12>
              <v-container grid-list-md>
                <v-layout row wrap align-center>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon size="70" class="green--text text--lighten-1">thumb_up</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline text-xs-center">Quality</div>
                      </v-card-title>
                      <v-card-text>
                        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maiores accusantium voluptas laborum rem ipsam! Quos corrupti iste modi vel quas atque porro tempore unde quae sit, minus magni voluptates voluptate!
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon size="70" class="green--text text--lighten-1">stars</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline">Expertise</div>
                      </v-card-title>
                      <v-card-text>
                        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure, pariatur quia nostrum voluptatum eius amet maxime veniam aliquam, tempore sit inventore et repudiandae soluta error ipsum deserunt, ab quidem? Laboriosam.
                      </v-card-text>
                    </v-card>
                  </v-flex>
                  <v-flex xs12 md4>
                    <v-card class="elevation-0 transparent">
                      <v-card-text class="text-xs-center">
                        <v-icon size="70" class="green--text text--lighten-1">face</v-icon>
                      </v-card-text>
                      <v-card-title primary-title class="layout justify-center">
                        <div class="headline text-xs-center">Service</div>
                      </v-card-title>
                      <v-card-text>
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa odit exercitationem nobis repellat dolorem, deserunt officiis ratione ullam incidunt voluptate dolorum est mollitia? Quisquam nemo doloremque a sapiente voluptatem magnam.
                      </v-card-text>
                    </v-card>
                  </v-flex>
                </v-layout>
              </v-container>
            </v-flex>
          </v-layout>
        </section>
        <section>
          <v-parallax src="images/parallax2.jpg" height="380" class="elevation-1">
          <v-layout column align-center justify-center>
            <div class="display-2 white--text mb-3 text-xs-center">Our range of Products</div>
            <em>Kick-start your project today</em>
            <v-btn
              class="green mt-5"
              dark
              large
              round
              href="/pre-made-themes"
            >
              Go to Products
            </v-btn>
          </v-layout>
        </v-parallax>
        </section>
        <section>
          <v-container grid-list-xl>
            <v-layout row wrap justify-center class="my-5">
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="/images/IMF_5467.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">De-Huller SSN-1</h3>
                      <div>A Minor Millet Dehuller,removes the hull,But leaves the bran layer intact</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="/images/IMF_5511.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">Integrated Precleaner</h3>
                      <div>A Minor Millet Dehuller,removes the hull,But leaves the bran layer intact</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="/images/IMF_6524.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">Turnkey Project</h3>
                      <div>A Minor Millet Dehuller,removes the hull,But leaves the bran layer intact</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
            </v-layout>
          </v-container>
        </section>
        <section>
          <v-parallax src="images/parallax3.jpg" height="380" class="elevation-1">
          <v-layout column align-center justify-center>
            <div class="display-2 white--text mb-3 text-xs-center">Our range of Products</div>
            <em>Kick-start your project today</em>
            <v-btn
              class="orange mt-5"
              dark
              large
              round
              href="/pre-made-themes"
            >
              Our Services
            </v-btn>
          </v-layout>
        </v-parallax>
        </section>
        <section>
          <v-container grid-list-xl>
            <v-layout row wrap justify-center class="my-5">
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="http://borne.askgee.net/images/about/1.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">Non-Destructive Test</h3>
                      <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero omnis unde nesciunt?</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="http://borne.askgee.net/images/about/2.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">Assessment of Installation</h3>
                      <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero omnis unde nesciunt?</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
              <v-flex xs12 sm4>
                <v-hover>
                  <v-card
                  slot-scope="{ hover }"
                  :class="`elevation-${hover ? 12 : 2}`"
                  class="mx-auto">
                  <v-img src="http://borne.askgee.net/images/about/3.jpg"></v-img>
                  <v-card-title primary-title>
                    <div>
                      <h3 class="headline mb-0">Operation Training</h3>
                      <div>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero omnis unde nesciunt?</div>
                    </div>
                  </v-card-title>
                  <v-card-actions>
                    <v-btn flat outline color="orange">View</v-btn>
                  </v-card-actions>
                  </v-card>
                </v-hover>
              </v-flex>
            </v-layout>
          </v-container>
        </section>
        <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <div class="headline">Leave a message</div>
              <form>
                <v-text-field
                  v-validate="'required|max:10'"
                  label="Name"
                  required
                ></v-text-field>
                <v-text-field
                  v-validate="'required|email'"
                  label="E-mail"
                  required
                ></v-text-field>
                <v-text-field
                  label="Phone"
                  required
                ></v-text-field>
                <v-textarea
                  label="Message"
                  required
                ></v-textarea>
                <v-btn class="green">submit</v-btn>
                <v-btn class="orange">clear</v-btn>
              </form>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>
                  If You have any query please contact with us
                </v-card-text>
                <v-list class="transparent">
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--lighten-2">phone</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>73392 22901 / 75067 81045</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>No 2/834, Kavunji, Kavunji post,</v-list-tile-title>
                      <v-list-tile-title>Kodaikanal, Dindigul, Tamil Nadu, India – 624101</v-list-tile-title>
                      <v-list-tile-title>India – 624101</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="green--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>info@bornetechnologies@gmail.com</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
      </template>
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


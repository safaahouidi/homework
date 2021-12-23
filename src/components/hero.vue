 <template>
 <div>
   <v-app-bar
                  app
                  color="primary"
                  dark
                >
                  <div class="d-flex align-center">
                    <v-img
                      alt="Vuetify Logo"
                      class="shrink mr-2"
                      contain
                      src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
                      transition="scale-transition"
                      width="40"
                    />
                    <v-img
                      alt="Vuetify Name"
                      class="shrink mt-1 hidden-sm-and-down"
                      contain
                      min-width="100"
                      src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
                      width="100"
                    />
                  </div>
                  <v-spacer></v-spacer>
                  <v-btn
                    href="https://github.com/vuetifyjs/vuetify/releases/latest"
                    target="_blank"
                    text
                  >
                    <span class="mr-2">Latest Release</span>
                    <v-icon>mdi-open-in-new</v-icon>
                  </v-btn>
             </v-app-bar>
            <v-img
              src="https://m3rfah.com/wp-content/uploads/2021/05/%D8%A7%D9%84%D8%B3%D9%8A%D8%A7%D8%AD%D8%A9-%D9%81%D9%8A-%D8%AF%D8%A8%D9%8A-%D9%81%D9%8A-%D8%B4%D9%87%D8%B1-%D8%AF%D9%8A%D8%B3%D9%85%D8%A8%D8%B1.jpg"
              aspect-ratio="1.7"
            ></v-img>
               <div class=" text-center  text-caption mt-5" >
               this is Dubai
               <br>
                <v-btn href="#" color="primary"  >
                         clickme
                        </v-btn>
            </div>

      </div>
 </template>
<style scoped>

</style>

 <template>
 <div id="hero">
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
                      src="https://logos.flamingtext.com/City-Logos/Dubai-Water-Logo.png"
                      transition="scale-transition"
                      width="60"
                    />
                   <h2>Dubai</h2>
                  </div>
                  <v-spacer></v-spacer>
                  <v-btn
                  href="#hero"
                    text
                  >
                    <span class="mr-2">Hero</span>
                  </v-btn>
                  <v-btn
                  href="#vcard"
                    text
                  >
                    <span class="mr-2">vcard</span>
                  </v-btn>
                  <v-btn
                  href="#vimage"
                    text
                  >
                    <span class="mr-2">Gallary</span>
                  </v-btn>
                   <v-btn
                  href="#stats"
                    text
                  >
                    <span class="mr-2">Stats</span>
                  </v-btn>
                  <v-btn
                  href="#banner"
                    text
                  >
                    <span class="mr-2">banner</span>
                  </v-btn>
                  <v-btn
                  href="#table"
                    text
                  >
                    <span class="mr-2">data table</span>
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

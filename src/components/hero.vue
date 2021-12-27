 <template>
 <div id="hero">
                  <v-app-bar
                   app
                   color="primary"
                   dark
                    >

                  <div class="d-flex align-center ">
                    <v-img
                      alt="Vuetify Logo"
                      class="shrink mr-2"
                      contain
                      src="https://media.istockphoto.com/photos/dubai-marina-picture-id467829216?k=20&m=467829216&s=612x612&w=0&h=W1NGHMkLoYcPxb-RKqbe0jnH8-W35c0hcoxaN29PqMA="
                      transition="scale-transition"
                      width="40"
                    />
                   <h2>Dubai</h2>
                  </div>
                  <v-spacer></v-spacer>
                  <div class="d-none d-sm-flex d-md-none" >

                 <div class="text-center">
    <v-menu offset-y>
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="primary"
          dark
          v-bind="attrs"
          v-on="on"
          text
        >
          <v-app-bar-nav-icon></v-app-bar-nav-icon>
        </v-btn>
      </template>
      <v-list>
        <v-list-item
          v-for="(item, index) in items"
          :key="index"
        >
          <v-list-item-title>{{ item.title }}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>
</div>
                  </div>
                  <div class=" d-none d-lg-flex d-xl-none">
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
                  </div>
             </v-app-bar>

            <v-img
              src="https://media.istockphoto.com/photos/dubai-marina-picture-id467829216?k=20&m=467829216&s=612x612&w=0&h=W1NGHMkLoYcPxb-RKqbe0jnH8-W35c0hcoxaN29PqMA="
              aspect-ratio="1.7"
            ></v-img>
               <div class=" text-center  text-caption mt-5" >
               this is Dubai
               <br>
                <v-btn href="#" color="primary" style="background: #916947" >
                         clickme
                        </v-btn>
            </div>

      </div>
 </template>
<script>
export default {
  data: () => ({
    items: [
      { title: 'Hero' },
      { title: 'Card' },
      { title: 'Gallary' },
      { title: 'banner' },
      { title: 'stats' },
      { title: 'Footer' }

    ]
  })
}
</script>

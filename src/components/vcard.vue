<template>
  <div id="vcard" class="mt-5">
        <v-container>
           <v-row >
      <v-col
        v-for="image in images"
        :key="image"
        cols="12"
        sm="4"
      >
       <v-card
    class="mx-auto"
    max-width="400"
  >
    <v-img
      class="white--text align-end"
      height="200px"
      :src="image"
    >
      <v-card-title>Dubai</v-card-title>
    </v-img>

    <v-card-text class="text--primary text-center">
      <div>Some images from Dubai</div>
    </v-card-text>

    <v-card-actions>
      <v-btn
        color="orange"
        text
      >
        Share
      </v-btn>

      <v-btn
        color="orange"
        text
      >
        Explore
      </v-btn>
    </v-card-actions>
  </v-card>
      </v-col>
    </v-row>

        </v-container>
    </div>
</template>
<script>
export default {
  name: 'vcard',
  props: {
    images: {
      type: Array
    }
  },
  data () {
    return {
      image: ''
    }
  }

}

</script>

<template>
  <div id="vimage" class="mt-5" >
    <v-container>
         <v-row >
      <v-col
        v-for="image in imagess"
        :key="image"
        cols="12"
        sm="4"
      >
        <v-img
      class="white--text align-end "

      height="200px"
      :src="image"
    >
        </v-img>
      </v-col>
         </v-row>
    </v-container>
</div>
</template>
<script>
export default {
  props: {
    imagess: {
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

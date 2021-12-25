<template>
  <div id="stats" class="mt-5">
    <v-container>
     <v-row >
      <v-col
        v-for="i in 3"
        :key="i"
        cols="12"
        sm="2"
        class="mx-auto my-auto"
      >

          <v-card  class=" text-center py-3 rounded-circle"
              max-width="82" height="82">

              {{texts[i-1]}}:  {{numbers[i-1]}}

              </v-card>

  </v-col>
 </v-row>

    </v-container>

  </div>
</template>
<script>
export default {
  props: {
    texts: {
      type: Array
    },
    numbers: {
      type: Array
    }
  },
  data () {
    return {
      text: '',
      number: ''
    }
  }

}

</script>

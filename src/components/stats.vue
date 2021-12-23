<template>
  <div class="stats">
    <v-container>
     <v-row >
      <v-col
        v-for="i in 3"
        :key="i"
        cols="12"
        sm="4"
      >

          <v-card  class="px-5"
              max-width="350">
              <v-row>
              <v-col  v-for="i in 3" :key="i">
              {{texts[i-1]}}:{{numbers[i-1]}}
</v-col>
</v-row>
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

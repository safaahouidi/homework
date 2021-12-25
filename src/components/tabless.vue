<template>
  <div id="table">
    <v-container>
      <v-data-table
        :headers="headers"
        :items="users"
        :items-per-page="5"
        class="data-table mt-6"
      ></v-data-table>
    </v-container>
  </div>
</template>
<script>
export default {
  data () {
    return {
      users: [],
      headers: [
        {
          text: 'Data-Table',
          align: 'start',
          sortable: false,
          value: 'id'

        },
        { text: 'users', value: 'name' },
        { text: 'Email', value: 'email' },
        { text: ' City', value: 'address.city' }
      ]
    }
  },
  mounted () {
    const baseURI = 'https://jsonplaceholder.typicode.com/users'
    this.$http.get(baseURI)
      .then((result) => {
        this.users = result.data
      })
  }
}
</script>

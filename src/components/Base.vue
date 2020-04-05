<template>
  <v-container>
    <p><router-link to="/">home</router-link></p>
    <p><router-link to="/about">about</router-link></p>
    <router-view></router-view>
  </v-container>
</template>

<script lang="ts">
  import Vue from 'vue'

  export default Vue.extend({
    name: 'Base'
  })
</script>

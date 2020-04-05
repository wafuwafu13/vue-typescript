<template>
  <v-app>
    <v-content>
      <Base/>
    </v-content>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue';
import Base from './components/Base.vue';

export default Vue.extend({
  name: 'App',

  components: {
    Base,
  },

  data: () => ({
    //
  }),
});
</script>

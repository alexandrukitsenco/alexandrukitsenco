<template>
  <v-app>
    <v-main>
      <Main/>
    </v-main>
  </v-app>
</template>

<script>
import Main from './views/Main.vue';

export default {
  name: 'App',

  components: {
    Main
},

  data: () => ({
    //
  }),
};
</script>

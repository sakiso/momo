<template>
  <v-app>
    <main-view></main-view>
  </v-app>
</template>

<script>
import MainView from "./views/main.vue";

export default {
  name: "App",

  components: {
    MainView
  },

  data: () => ({
    //
  })
};
</script>

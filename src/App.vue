<template>
  <v-app>
    <sidebar />

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import Sidebar from "./components/Sidebar";

export default {
  name: "App",

  components: {
    Sidebar,
  },

  data: () => ({}),
};
</script>

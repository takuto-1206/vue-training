<template>
  <v-app>
    <Header />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/contents/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>

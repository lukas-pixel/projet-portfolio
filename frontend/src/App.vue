<template>
  <v-app>
    <v-app-bar app color="red" dark>
      <v-toolbar-title>{{ portfolio }}</v-toolbar-title>
    </v-app-bar>

    <v-main>
      <div class="text-center pa-10">👋 Bonjour 👋</div>
      <!-- Votre Code ICI -->
    </v-main>
  </v-app>
</template>

<script>
  export default {
    name: "App",
    data() {
      return { portfolio: "Voici mon Portfolio Project avec Vue.js" };
    },
  };
</script>

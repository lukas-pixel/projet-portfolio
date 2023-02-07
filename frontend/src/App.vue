<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <v-toolbar-title>{{ school }}</v-toolbar-title>
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
      return { school: "MyDigitalSchool" };
    },
  };
</script>

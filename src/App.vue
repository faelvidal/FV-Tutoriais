<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="favicon.ico"
          transition="scale-transition"
          width="40"
        />

       
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://www.youtube.com/c/FAELDAINTERNET/feature"
        target="_blank"
        text
      >
        <span class="mr-2">Fael da Internet</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
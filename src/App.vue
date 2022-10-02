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

      <div>
  
        <v-btn
         class="ma-2"
         fab
         dark
          color="primary"
        >
          <v-icon dark>
            mdi-format-list-bulleted-square
          </v-icon>
        </v-btn>

        

      </div>
      
      <v-spacer></v-spacer>
      
        <v-btn icon>
          <v-icon>mdi-magnify</v-icon>
        </v-btn>

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
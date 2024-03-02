<template>
  <v-container>
    <v-row class="text-center">
       <v-col class="mb-5">
      
      <v-col cols="12">

   
      </v-col>

     

    <iframe width="auto" height="250" src="https://www.youtube.com/embed/Xp_57SQe0G0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
       <iframe width="auto" height="250" src="https://www.youtube.com/embed/I43liSQAYx0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

        
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <iframe width="auto" height="250" src="https://www.youtube.com/embed/s5nJAtgsL_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

        
      </v-col>
      

      <v-col
        class="mb-5"
        cols="12"
      >
        

        <v-row justify="center">
          <a
            v-for="(eco, i) in ecosystem"
            :key="i"
            :href="eco.href"
            class="subheading mx-3"
            target="_blank"
          >
            {{ eco.text }}
          </a>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
        
        },
        {
          text: 'FV Tutoriais | Fael da Telecom',
          href: 'https://www.youtube.com/@fvtutoriais/feature',
        }
        ,
      ],
      
      
    }),
  }
</script>

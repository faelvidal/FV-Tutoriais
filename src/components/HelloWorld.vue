<template>
  <v-container>
    <v-row class="text-center">
       <v-col class="mb-5">
      
      <v-col cols="12">

        <iframe width="auto" height="250" 
         src="https://www.youtube.com/embed/videoseries?list=PLohNzumXECygQqMYCQnC58sFUXYE3Ezmq" 
         title="Os Videos Mais vistos do canal" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen></iframe>      
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
        <h2 class="headline font-weight-bold mb-3">
         Redes Sociais
        </h2>

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
          text: 'Linkedin',
          href: 'https://www.linkedin.com/in/faelvidal/',
        },
        {
          text: 'Github',
          href: 'https://github.com/faelvidal',
        },
        {
          text: 'Behance',
          href: 'https://www.behance.net/faeldainternet',
        },
        {
          text: 'Youtube',
          href: 'https://www.youtube.com/c/FAELDAINTERNET/feature',
        }
        ,
      ],
      
      
    }),
  }
</script>

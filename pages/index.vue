<template>

  
  <v-row justify="center" align="center">
    
          
      <v-row class="fill-height">
        <v-carousel hide-delimiters cycle height="350">
          <v-carousel-item
            v-for="(item,i) in items"
            :key="i"
            :src="item.src"
          ></v-carousel-item>
        </v-carousel>
      </v-row>

      
<v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline">
          Bienvenidos a la casa de los abuelos
        </v-card-title>
        <v-card-text>
          
          <p>
            Ejemplo
            <a
              href="https://vuetifyjs.com"
              target="_blank"
              rel="noopener noreferrer"
            >
              documentation </a
            >.
          </p>
          <p>
                 asdwqe      
          </p>
            
          <p>
            TEXTO REFERENTE A LA CASA DE LOS ABUELOS
          </p>
          <div class="text-xs-right">
            <em><small>&mdash; John Leider</small></em>
          </div>
          <hr class="my-3" />
          <a
            href="https://nuxtjs.org/"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt Documentation
          </a>
          <br />
          <a
            href="https://github.com/nuxt/nuxt.js"
            target="_blank"
            rel="noopener noreferrer"
          >
            Nuxt GitHub
          </a>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
 
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
  data () {
      return {
        items: [
          {
            src: '2017-06-04.jpeg',
          },
          
        ],
      }
    },
}
</script>

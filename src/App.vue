<template>
  <v-app>
    <v-main>
      <HelloWorld/>
      <v-content>
      <HeroPhoto/>
    </v-content>
    </v-main>
   
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeroPhoto from './components/HeroPhoto.vue'

export default {
  name: 'App',

  components: {
    HelloWorld,
    HeroPhoto
  },

  data: () => ({
    //
  }),
}
</script>

<template>
  <v-app>
    <v-main>
      <HelloWorld />
      <v-content>
        <HeroPhoto />
        <GaleryPhoto />
      </v-content>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import HeroPhoto from "./components/HeroPhoto.vue";
import GaleryPhoto from "./components/GaleryPhoto.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    HeroPhoto,
    GaleryPhoto
  },

  data: () => ({
    //
  })
};
</script>

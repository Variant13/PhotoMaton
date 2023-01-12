<template>
  <v-app>
    <v-main>
      <HelloWorld />
      <v-content>
        <HeroPhoto />
        <GaleryPhoto />
        <LaterPostPhoto/>
        <FooterPhoto/>
      </v-content>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import HeroPhoto from "./components/HeroPhoto.vue";
import GaleryPhoto from "./components/GaleryPhoto.vue";
import LaterPostPhoto from "./components/LaterPostPhoto.vue";
import FooterPhoto from "./components/FooterPhoto.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    HeroPhoto,
    GaleryPhoto,
    LaterPostPhoto,
    FooterPhoto
  },

  data: () => ({
    //
  })
};
</script>

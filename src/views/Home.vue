<template>
  <v-app id="drugstore.cloveropen.com">
    <Basepage />
    <v-container fluid>
      <v-layout justify-start>
        <v-img :src="require('../assets/main_bg.jpg')" />
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
import Basepage from "../components/Basepage";
export default {
  components: {
    Basepage
  }
};
</script>

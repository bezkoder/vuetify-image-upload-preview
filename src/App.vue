<template>
  <v-app>
    <v-container fluid style="width: 600px">
      <div class="mb-5">
        <h1>bezkoder.com</h1>
        <h2>Vuetify Image Upload with Preview</h2>
      </div>

      <upload-image></upload-image>
    </v-container>
  </v-app>
</template>

<script>
import UploadImage from "./components/UploadImage";

export default {
  name: "App",
  components: {
    UploadImage,
  },
};
</script>

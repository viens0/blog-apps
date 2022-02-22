<template>
  <v-footer padless>
    <v-col lg="12">
      <v-row justify="center">
        <v-col lg="4" class="text-center">
          <v-toolbar-title>Web App</v-toolbar-title>
          <v-card-text>
            <v-btn
              v-for="icon in icons"
              :key="icon"
              class="mx-4 black--text"
              icon
            >
              <v-icon size="24px">
                {{ icon }}
              </v-icon>
            </v-btn>
          </v-card-text>
          <v-subheader
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora
            nulla eligendi non laudantium perferendis deleniti
          </v-subheader>
          <v-form class="mt-4">
            <v-text-field label="Email" outlined dense />
            <v-btn rounded color="success">Subscribe</v-btn>
          </v-form>
        </v-col>
      </v-row>

      <div class="mt-10">
        <v-divider></v-divider>
        <v-subheader>
          © 2022 Copyright: viens {{ new Date().getFullYear() }} —
          <strong>Vuetify</strong>
          <v-spacer />
          <strong>designer by viens</strong>
        </v-subheader>
      </div>
    </v-col>
  </v-footer>
</template>

<script>
export default {
  name: "Footer",
  data() {
    return {
      icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
    };
  },
};
</script>

<style>
</style>
<template>
  <v-container>
      <v-row>
          <v-col lg="6">
              <img width="500px" src="./../assets/12345.jpg" alt="">
          </v-col>
          <v-col lg="6">
              <v-subheader class="text-h4">About Us</v-subheader>
              <p>Get started with Vuetify, the worlds most popular Vue.js framework for building feature rich, blazing fast applications.</p>
              <v-list>
                  <v-list-item>
                      <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                      <v-list-item-subtitle>will make changes to your project template files, components folder.</v-list-item-subtitle>
                  </v-list-item>
                  <v-list-item>
                      <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                      <v-list-item-subtitle>If you are installing Vuetify via Vue-CLI, make sure you commit your code to avoid any potential data loss.</v-list-item-subtitle>
                  </v-list-item>
                  <v-list-item>
                      <v-icon color="success" class="mr-3">mdi-check-all</v-icon>
                      <v-list-item-subtitle>components folder, vue.config.js, etc. </v-list-item-subtitle>
                  </v-list-item>
                  <p>This command will make changes to your project template files, components folder, vue.config.js, etc. If you are installing Vuetify via Vue-CLI, make sure you commit your code to avoid any potential data loss. Template changes can be skipped by selecting the advanced install option during install.</p>
              </v-list>
          </v-col>
      </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'Aboutus'
}
</script>

<style>

</style>
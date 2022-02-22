<template>
  <v-container class="pt-15">
      <v-row>
          <v-col lg="6">
              <h2 class="intro-text">Walcome To Our App</h2>
              <p class="description">These templates are known as wireframes and are designed to provide a consistent approach to layouts, layering, and shadows. They are a starting point that is meant to be modified to meet the specific needs of your application.</p>
              <v-btn color="success" lass="white--text mr-10" rounded>Get Started</v-btn>
              <v-btn color="indigo" class="white--text" rounded>
                  <v-icon>mdi-play-circle</v-icon> Whatch Video
              </v-btn>
          </v-col>
          <v-col lg="6">
              <img width="100%" src="./../assets/teknologi3.png" alt="">
          </v-col>
      </v-row>
  </v-container>
</template>

<script>
export default {
    name: 'HeroComponent'

}
</script>

<style>
h2.intro-text {
    font-family: cursive;
    font-size: 60px;
    font-weight: bold;
    color: #444;
}
p.description{
    font-family: cursive;
    font-size: 19px;
    margin: 32px 0px;
    color: #444444ba;
}
</style>
<template>
  <v-container class="mr-15">
    <v-row justify="center">
      <v-col lg="12" class="text-center">
        <v-subheader class="text-h4 justify-center">Contact</v-subheader>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. At mollitia ipsam sint cumque
        </p>
      </v-col>
      <v-col lg="6">
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4055438.176097954!2d107.8789278211657!3d-6.96337288180313!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e65759b9cd518dd%3A0xc377d19d8fedbc46!2sJawa%20Tengah!5e0!3m2!1sid!2sid!4v1645504831234!5m2!1sid!2sid" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </v-col>
      <v-col lg="6">
          <v-form
    ref="form"
  >
    <v-text-field
      v-model="contactInfo.name"
      :counter="10"
      label="Name"
      required
    ></v-text-field>

    <v-text-field
      v-model="contactInfo.email"
      label="E-mail"
      required
    ></v-text-field>
    <v-textarea label="massage" v-model="contactInfo.massage">

    </v-textarea>

    <v-btn
      color="success"
      class="mr-4"
    >
      Send
    </v-btn>
  </v-form>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
    name: "Contactus",
    data(){
        return{
            contactInfo:{}
        }
    }
};
</script>

<style>
</style>
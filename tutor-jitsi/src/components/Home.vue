<template>
  <div class="home">
    <v-row>
      <v-col>
      <v-list >You've arrived at the DevLodge</v-list>
      <v-list>Looking to work with other developers? We can help!</v-list>
      <router-link :to="{name: 'NewUser'}"><v-btn>Get Started</v-btn></router-link>
      <!-- <router-link :to="/create-account" tag="button">Get Started></router-link> -->
      </v-col>
    </v-row>
    <v-spacer class="space"></v-spacer>
    <v-list>Post your projects & find developers looking to improve their skills</v-list>
  </div>
</template>


<script>
export default {
  name: 'Home',
  props: {
  }
}
</script>



<style>
.home{
  text-align: center
}
.space{
  margin: 10em;
}
</style>
<template>
    <v-app>
      <v-app-bar app dense>
        <v-app-bar-nav-icon @click="toggle= !toggle"></v-app-bar-nav-icon>
        <v-toolbar-title>DevLodge</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-toolbar-items>
            <v-btn text to="/">Home</v-btn>
            <v-btn text to="/projects">Projects</v-btn>
            <v-btn text to="/groups">Groups</v-btn>
            <v-btn text to="/challenges">Challenges</v-btn>
        </v-toolbar-items>
      </v-app-bar>
      <!-- <v-navigation-drawer app v-model="toggle">
        
    
      </v-navigation-drawer> -->
      <v-main>

      <v-container fluid>

        <router-view to="/">Home</router-view>
        
      </v-container>
      </v-main>

    </v-app>

</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  }),
};
</script>

<template>
  <v-card class="mx-auto overflow-hidden">
    <v-app-bar color="" dark fixed>
      <v-row>
        <v-col cols="12" sm="4" md="4" class="">
          <!-- <v-spacer></v-spacer> -->
          <v-toolbar-title>CodeWohlig</v-toolbar-title>
          <!-- <v-spacer></v-spacer>
          <v-toolbar-title>Deals</v-toolbar-title>
          <v-spacer></v-spacer>
          <v-toolbar-title>Courses</v-toolbar-title>
          <v-spacer></v-spacer>
          <v-toolbar-title>Log In</v-toolbar-title> -->
        </v-col>
      </v-row>
      <v-toolbar-title>Deals</v-toolbar-title>

      <v-toolbar-title> Courses </v-toolbar-title>

      <v-toolbar-title> Log In </v-toolbar-title>

      <v-app-bar-nav-icon
        @click="drawer = !drawer"
        class=""
      ></v-app-bar-nav-icon>
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" absolute temporary>
      <v-list nav dense>
        <v-list-item-title>Deals</v-list-item-title>
        <v-list-item-title>Courses</v-list-item-title>
        <v-list-item-title>Courses</v-list-item-title>
        <!-- <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
           
          </v-list-item>

          <v-list-item>
            
          </v-list-item>
          <v-list-item>
           
          </v-list-item>
        </v-list-item-group> -->
      </v-list>
    </v-navigation-drawer>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    drawer: false,
    group: null,
  }),
}
</script>
<template>
  <div>
    <v-app-bar
      color="green darken-2"
      dense
      dark
      app
    >
      <v-app-bar-nav-icon color="light-green lighten-1"></v-app-bar-nav-icon>

      <v-toolbar-title>Nemesis Decoder | Enligtened LK </v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon color="green lighten-3">
        <v-icon>mdi-heart</v-icon>
      </v-btn>

    </v-app-bar>
  </div>
</template>

<script>
export default {
    name: 'NavBar',
     data: () => ({
      collapseOnScroll: true,
    }),
}
</script>

<style>

</style>
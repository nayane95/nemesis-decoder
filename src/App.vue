<template>
  <v-app>
    <v-content> 
      <NavBar/>
      <TextArea/>
    </v-content>
  </v-app>
</template>

<script>
import NavBar from './components/NavBar';
import TextArea from './components/TextArea';

export default {
  name: 'App',

  components: {
    NavBar,
    TextArea
  },

  data: () => ({
    //
  }),
};
</script>

<template>
  <v-app>
    <v-main>
      <AppHeader/>
      <Card/>
    </v-main>
  </v-app>
</template>

<script>
import AppHeader from './components/AppHeader';
import Card from './components/Card';

export default {
  name: 'App',

  components: {
    AppHeader,
    Card
  },

  data: () => ({
    //
  }),
};

</script>

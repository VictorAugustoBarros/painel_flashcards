<template>
  <v-row>
    <v-col cols="12" sm="12">
      <v-card height="100%">
        <v-card-title class="justify-center black white--text">
          <span class="text-h5">フラッシュカード</span>
        </v-card-title>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  data: () => ({
    items: [
      {title: 'Perfil'},
      {title: 'Logout'},
    ],
  }),
}
</script>
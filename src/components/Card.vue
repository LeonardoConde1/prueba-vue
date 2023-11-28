<template>
    <v-card class="mx-auto" max-width="400">
      <v-img
        :src="imageSrc"
        height="200px"
        cover
      ></v-img>
      <v-card-title>{{ title }}</v-card-title>
      <v-card-subtitle>{{ subtitle }}</v-card-subtitle>
      <v-card-actions>
        <v-btn :icon="'mdi-menu'"></v-btn>
        <v-spacer></v-spacer>
        <v-btn :icon="'mdi-chevron-down'"></v-btn>
      </v-card-actions>
    </v-card>
  </template>
  
  <script>
  export default {
    props: {
      imageSrc: String,
      title: String,
      subtitle: String,
    },
  };
  </script>

  
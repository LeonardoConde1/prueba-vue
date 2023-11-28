<template>
  <v-layout>
    <v-navigation-drawer expand-on-hover rail>
      <img class="logo" src="../assets/logo.png" />
      <h3>SARA</h3>
      <v-list class="list" lines="two">
        <v-list-item
          v-for="(item, i) in items"
          :key="i"
          :value="item"
          :class="{ 'home-item': item.special }"
        >
          <template v-slot:prepend>
            <v-icon :icon="item.icon"></v-icon>
          </template>
          <v-list-item-title v-text="item.text"></v-list-item-title>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </v-layout>
</template>

<script>
export default {
  data: () => ({
    items: [
      { text: "Home", icon: "mdi-home", special: true },
      { text: "Groups", icon: "mdi-account-group-outline" },
      { text: "Smartbooks", icon: "mdi mdi-book-alphabet" },
      { text: "utilities", icon: "mdi mdi-wrench-outline" },
      { text: "Tour Virtual", icon: "mdi-auto-fix" },
      { text: "Support", icon: "mdi mdi-head-alert-outline" },
    ],
  }),
};
</script>

<style scoped>
.logo {
  height: 50px;
}

.home-item {
  margin-bottom: 80px;
}

.lista {
  padding: 0px;
}
</style>

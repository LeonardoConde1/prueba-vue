<template>
  <div class="conteiner">
    <v-btn
      class="btn"
      @click="changeColor(1)"
      :class="{ active: activeButton === 1 }"
    >
      GENERAL
    </v-btn>
    <v-btn
      class="btn"
      @click="changeColor(2)"
      :class="{ active: activeButton === 2 }"
    >
      MIS LIBROS
    </v-btn>
    <v-btn
      class="btn"
      @click="changeColor(3)"
      :class="{ active: activeButton === 3 }"
    >
      MIS FAVORITOS
    </v-btn>
    <v-btn
      class="btn"
      @click="changeColor(4)"
      :class="{ active: activeButton === 4 }"
      append-icon=" mdi-menu-down" >
      BIBLOTECAS DE SARA
    </v-btn>
    <svg class="filter" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 24 24" >
      <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M22 3H2l8 9.46V19l4 2v-8.54z"/></svg>
    <v-card-text class="search">
      <v-text-field
        :loading="loading"
        prepend-inner-icon="mdi-magnify"
        density="compact"
        variant="solo"
        label="Buscar tema, libro, nivel, autor"
        single-line
        hide-details
        @click:append-inner="onClick"
      ></v-text-field>
    </v-card-text>
  </div>
</template>

<script>
export default {
  data: () => ({
    activeButton: null,
  }),
  methods: {
    changeColor(buttonNumber) {
      this.activeButton = buttonNumber;
    },
  },
};
</script>

<style scoped>

*{
  font-size: large;

}
.active {
  background-color: #2196f3; /* Color azul al hacer clic */
  color: white; /* Color del texto */
}
.conteiner {
  display: flex;
  margin-top: 2%;
  margin-left: 20%;
  align-items: end;
}
.btn {
  margin-right: 100px;
  border: none;
  box-shadow: none;
}

.search{
    padding: 10px 90px 0px 50px;
}
.filter{
  height: 40px;
  
  
}
</style>

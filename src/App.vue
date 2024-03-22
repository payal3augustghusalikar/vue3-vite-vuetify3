<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Treeview from './components/Treeview.vue';
</script>

<template>
  <Treeview />
  <v-card class="mt-5" style="border-color:grey" variant="outlined">
    This is other component
    <HelloWorld msg="Vite + Vue" />
  </v-card>
</template>

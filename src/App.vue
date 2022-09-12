<script lang="ts">
//import { RouterLink, RouterView } from 'vue-router'
import { defineComponent } from "vue";
import Products from "../src/components/products.vue";
import AppHeader from "./components/appHeader.vue";
export default defineComponent({
  components: { Products, AppHeader },
});
</script>

<template>
  <AppHeader />
  <Products />
  <!--<RouterView />-->
</template>

<style scoped>
    
</style>


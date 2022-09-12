<script lang="ts">
import { injectProp } from "@vue/compiler-core";
import { defineComponent } from "vue";
import Product from "./product.vue";
export default defineComponent({
  components: { Product },
});
</script>
<template>
  <section class="products">
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
    <Product />
  </section>
</template>
<style scoped>
.products {
  display: flex;
  flex-wrap: wrap;
}

@media (max-width: 920px) {
  .products .product-card:first-child,
  .products .product-card:nth-child(2) {
    flex: 2 46%;
  }
}
</style>

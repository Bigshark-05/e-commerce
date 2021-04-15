<template>
  <div class="d-flex flex-row flex-wrap p-1">
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
    <shop-product-item></shop-product-item>
  </div>
</template>

<script>
import ShopProductItem from "./ShopProductItem.vue";
export default {
  components: {
    ShopProductItem,
  },
};
</script>

<style></style>

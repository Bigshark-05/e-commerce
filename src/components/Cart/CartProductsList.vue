<template>
  <div class="d-flex flex-column p-5">
    <cart-product-item
      v-for="item in cart"
      :key="item.id"
      :item="item"
    ></cart-product-item>
  </div>
</template>

<script>
import CartProductItem from "./CartProductItem.vue";
export default {
  components: {
    CartProductItem,
  },
  props: ["cart"],
};
</script>

<style></style>

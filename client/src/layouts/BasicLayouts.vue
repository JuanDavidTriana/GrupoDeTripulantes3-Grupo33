<template>
  <div class="basic-layout">
    <Menu />
    <div class="ui container">
      <slot />
    </div>
  </div>

  <Cart />
  <p>Este es el footer</p>
</template>

<script>
import Menu from '../components/Menu.vue';
import Cart from '../components/Cart/Cart.vue';

export default {
  name: 'BasicLayouts',
  components: {
    Menu,
    Cart,
  },
};
</script>

<style></style>

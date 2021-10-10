<template>
  <div class="basic-layout">
    <Menu />
    <div class="ui container">
      <slot />
    </div>
  </div>

  <Cart />
  
  <div class="footer">
      © 2021 Copyright : Panela a un Clic
    </div>
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

<style lang="scss" scoped>
.footer{
  background-color: #043f1d;
  text-align: center;
  color: #fff;
  text-transform: uppercase;
  padding-top: 10px;
  padding-bottom: 10px;
}
</style>

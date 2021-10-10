<template>
  <BasicLayouts>
    
    <img src="../assets/panela2.jpg" class="img_principal">
    <h1 class="titulo">NUESTROS PRODUCTOS</h1>
    <div class="ui grid">
      <div
        class="sixten wide mobile eight wide tablet four wide computer column"
        v-for="product in products"
        :key="product.id"
      >
        <Product :product="product" />
      </div>
    </div>
  </BasicLayouts>
</template>

<script>
import { ref, onMounted } from 'vue';
import BasicLayouts from '../layouts/BasicLayouts.vue';
import { getProducts } from '../api/products';
import Product from '../components/Product.vue';
export default {
  name: 'Home',
  components: {
    BasicLayouts,
    Product,
  },

  setup() {
    let products = ref(null);

    onMounted(async () => {
      const response = await getProducts(20);
      products.value = response;
    });
    return {
      products,
    };
  },
};
</script>
<style lang="scss" scoped>
.img_principal{
  height: 400px;
  width: 800px;
  display: block;
  margin: auto;
}
.titulo{
  text-align: center;
}

</style>

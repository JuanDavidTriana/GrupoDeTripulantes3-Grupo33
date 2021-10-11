<template>
  <BasicLayouts>
    <div class="contenedor">
      <img src="../assets/panelafondo.jpg" class="img_fondo" />
      <div class="texto-encima">Texto</div>
      <div class="centrado">Conócenos</div>
    </div>

    <hr class="featurette-divider" />

    <p class="descripcion">
      Panela a un Click es una iniciativa que nace en 2021 para apoyar a los
      productores de panela colombiana bajo el modelo de e-Commerce o comercio
      electrónico de este producto y sus derivados. Este sitio web con su
      facilidad de manejo otorga al productor una interacción directa a esta
      tecnología y demás innovaciones con soporte a futuro. El cliente puede
      ingresar y visualizar el producto, realizando un registro rápido puede
      hacer su compra y pedido. Este producto insignia de Colombia se produce en
      departamentos como Cundinamarca, Caldas, Santander, Boyacá y Antioquia. La
      vinculación de fuerza de trabajo relacionada a este sector se estima en
      cerca de 20.000 trapiches paneleros, es por esto por lo que Colombia es el
      segundo país productor de panela en el mundo y el de mayor consumo de sus
      habitantes.
    </p>
    <hr class="featurette-divider" />

    <div class="row">
      <div class="col-lg-4">
        <img
          src="../assets/viviana.jpg"
          class="bd-placeholder-img rounded-circle"
          width="140"
          height="140"
          alt="..."
        />

        <title>Placeholder</title>

        <h2 class="name">Viviana Londoño</h2>
        <p>Ingeniera de Alimentos.</p>
        <p>Tecnologa en analisis y desarrollo de sistemas de información.</p>
      </div>
      <!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img
          src="../assets/Victor.jpg"
          class="bd-placeholder-img rounded-circle"
          width="140"
          height="140"
          alt="..."
        />
        <title>Placeholder</title>

        <h2 class="name">Victor Alfonso Martinez</h2>
        <p>Ingeniero de alimentos</p>
      </div>
      <!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img
          src="../assets/david.jpeg"
          class="bd-placeholder-img rounded-circle"
          width="140"
          height="140"
          alt="..."
        />
        <title>Placeholder</title>

        <h2 class="name">Angel David Reyes</h2>
        <p>Administrador de Empresas</p>
      </div>
    </div>
  </BasicLayouts>
</template>

<script>
import BasicLayouts from "../layouts/BasicLayouts.vue";
export default {
  name: "About",
  components: {
    BasicLayouts,
  },
};
</script>

<style lang="scss" scoped>
.img_fondo {
  width: 1100px;
  height: 220px;
  display: block;
  margin: auto;
  color: #ffffff;
}

.contenedor {
  position: relative;
  display: inline-block;
  text-align: center;
}
.texto-encima {
  position: absolute;
  top: 10px;
  left: 10px;
}
.centrado {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #ffffff;
  font-size: 200%;
}

.descripcion {
  padding: 2.5%;
  font-size: large;
  text-align: justify;
}

.bd-placeholder-img.rounded-circle {
  display: block;
  margin: auto;
}

.name {
  text-align: center;
}

p {
  text-align: center;
  font-size: 120%;
}
</style>
<template>
  <BasicLayouts>
    <img src="../assets/panelafondo.jpg" class="img_fondo" />
    <hr class="featurette-divider" />

    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque in
      lacinia dui. Sed et accumsan purus. Vestibulum mollis a mauris eu
      tristique. Nam dolor libero, lobortis eu nibh vel, vehicula interdum dui.
      Integer convallis pretium auctor. In lacus justo, scelerisque vestibulum
      ligula at, molestie tempor dolor. Nulla fringilla condimentum leo, ac
      vestibulum ex dictum et. Pellentesque fringilla faucibus diam, vel
      ullamcorper ante hendrerit sed. Mauris elementum arcu vitae ante dapibus,
      nec dapibus mi convallis.
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

        <h2>Viviana Londoño</h2>
        <p>
          Ingeniera de Alimentos
          Tecnologa en analisis y desarrollo de sistemas de informacion
        </p>
      </div>
      <!-- /.col-lg-4 -->
      <div class="col-lg-4">
        <img
          src="img/IMG_20190813_165441.jpg"
          class="bd-placeholder-img rounded-circle"
          width="140"
          height="140"
          alt="..."
        />
        <title>Placeholder</title>

        <h2>Victor Alfonso Martinez</h2>
        <p>
          Ingeniero de alimentos
        </p>
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

        <h2>Angel David Reyes</h2>
        <p>
          Administrador de Empresas
        </p>
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
}
</style>
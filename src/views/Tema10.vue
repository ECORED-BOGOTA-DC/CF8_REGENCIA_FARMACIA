<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 10
      h1 Proceso administrativo
    p(data-aos="fade-right") Son un conjunto de actividades o funciones de forma secuencial, que incluyen: la planeación, la organización, el control y la dirección.
    p.mb-5(data-aos="fade-right") La siguiente imagen nos presenta de forma gráfica, cómo es cada uno de los pasos que conforman el proceso administrativo.
    .row
      .col-lg-11.mx-auto(data-aos="fade-left")
        .titulo-sexto.color-acento-botones
          h5 Figura 8.
          span Proceso administrativo
        figure
          img(src="@/assets/curso/t10/f1.svg" alt="Proceso administrativo")

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>

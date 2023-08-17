<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 10
      h1 Proceso administrativo
    p Son un conjunto de actividades o funciones de forma secuencial, que incluyen: la planeación, la organización, el control y la dirección.
    p.mb-5 La siguiente imagen nos presenta de forma gráfica, cómo es cada uno de los pasos que conforman el proceso administrativo.
    .col-lg-10.mx-auto
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

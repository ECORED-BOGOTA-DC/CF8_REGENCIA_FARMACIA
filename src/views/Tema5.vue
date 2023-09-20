<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Política de aprovisionamiento
    p(data-aos="fade-right") El aprovisionamiento son todas las acciones que realiza la institución para abastecerse de los productos necesarios y así llevar a cabo los procesos de dispensación, distribución y/o fabricación de magistrales tópicos no estériles. La función principal de este es una buena gestión de <i>stock</i> de todos los productos en las mejores condiciones de calidad, abastecimiento y al menor costo posible.
    p.mb-5(data-aos="fade-right") Al momento de realizar el aprovisionamiento se debe:
    .contenedor__bbg3(data-aos="fade-left")
      .row.traslape3.align-items-center(data-aos="fade-down")
        .col-lg-3.ms-auto.py-4
          img(src='@/assets/curso/t5/f1.svg', alt='Estantería con medicamentos')
          h5.text-center Planificar y gestionar las compras
        .col-lg-3
          img(src='@/assets/curso/t5/f2.svg', alt='Facmacéutico y computadora')
          h5.text-center Almacenar los productos necesarios para operatividad normal
        .col-lg-3.me-auto.py-4
          img(src='@/assets/curso/t5/f3.svg', alt='Celular y estante con medicamentos')
          h5.text-center Mantener <i>stocks</i> mínimos de cada producto

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

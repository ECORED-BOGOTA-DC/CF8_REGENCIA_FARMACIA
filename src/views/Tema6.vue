<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Fuentes de abastecimiento
    .contenedor__bbg5.p-5
      .row.traslape1
        .col-lg-7.col-z1.f-left(data-aos="fade-right")
          img(src="@/assets/curso/t6/i1.jpg", style="width:650px" ,alt="Dispensario de fármacos").m-auto
        .col-lg-4_5.col-z2.f-right(data-aos="fade-left")
          .contenedor3c.p-4
            h4.text-center ¿Qué es abastecimiento de medicamentos?
              br
              br
              i.fas.fa-quote-right.cac
            p.text-center “El conjunto de procedimientos y normas destinadas a garantizar el almacenamiento, transporte y distribución adecuada de materiales y productos farmacéuticos, a partir de la liberación de que son objeto después del proceso de fabricación, de manera que estos conserven la naturaleza y calidad deseadas cuando lleguen al consumidor final”
            h5.text-right -Vera, H., 2009, p.2
      p(data-aos="fade-right") Para ampliar la información sobre este tema, visite el enlace que se encuentra en el material complementario.
      .col-lg-6(data-aos="fade-left")
        a.anexo(:href="obtenerLink('#/complementario')")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> Fuentes de abastecimiento

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

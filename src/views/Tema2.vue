<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Cotización
    .row.align-items-center.mb-5
      .col-lg-7(data-aos="fade-right")
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Una cotización es un documento contable informativo, donde se detallan los precios de los productos, para llegar a la negociación y adquisición de ellos; este documento es utilizado por el área de compras de la institución. 
        p Su importancia se presenta a nivel administrativo, porque permite crear informes que posibilitan, posteriormente, comparar los productos cotizados con los facturados.
        p Una contización debe contener como mínimo los siguientes parámetros:
      .col-lg-5(data-aos="fade-left")
        img(src='@/assets/curso/t2/f1.svg', alt='Medicamentos y bolsa de compras')
    ImagenInfografica.color-acento-botones(data-aos="fade-right")
      template(v-slot:imagen)
        figure
          img(src='@/assets/curso/t2/infografica1.svg', alt='Ejemplo de formato de cotización')
          figcaption Partes de una cotización
      .tarjeta.color-acento-contenido.p-3(x="25%" y="15%")
        p.mb-0 Datos completos del proveedor (nombre, Nit, dirección, ciudad, teléfono, etc.).
      .tarjeta.color-acento-contenido.p-3(x="25%" y="24%")
        p.mb-0 Nombre de la persona que genera la cotización.
      .tarjeta.color-acento-contenido.p-3(x="90%" y="17%")
        p.mb-0 Fecha de expedición de la cotización.
      .tarjeta.color-acento-contenido.p-3(x="25%" y="55%")
        p.mb-0 Nombre del producto (los medicamentos deben ir acompañados de la concentración).
      .tarjeta.color-acento-contenido.p-3(x="42%" y="55%")
        p.mb-0 Descripción exacta para los demás productos.
      .tarjeta.color-acento-contenido.p-3(x="58%" y="55%")
        p.mb-0 Forma farmacéutica para los medicamentos.
      .tarjeta.color-acento-contenido.p-3(x="82%" y="55%")
        p.mb-0 Precio por unidad y por el total de la cantidad deseada.
      .tarjeta.color-acento-contenido.p-3(x="10%" y="87%")
        p.mb-0 Notas adicionales de ser necesarias.

</template>

<script>
export default {
  name: 'Tema2',
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

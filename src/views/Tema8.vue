<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 8
      h1 Acuerdos comerciales y reglamentación
    p(data-aos="fade-right") Los acuerdos o convenios surgen entre el comprador y el proveedor, donde se establecen, estipulan y/o pactan las especificaciones, condiciones, restricciones y/o concesiones, para la compraventa de los bienes que necesita o requiere la empresa.
    p.mb-5(data-aos="fade-right") A continuación, se mencionan las características de estos acuerdos:
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f1.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Cantidad
            .tarjetaTxt
              p.mb-0 Se relaciona con el precio de la compra, y puede ser que, a poca compra en lo relativo a cantidades, el precio suba; y en una compra de mucha cantidad, el precio baja en un porcentaje admisible para la empresa.
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f2.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Precio
            .tarjetaTxt
              p.mb-0 Este se relaciona con una compra alta o baja en su volumen de compra, en la calidad y en la forma de pago. 
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f3.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Fecha de entrega
            .tarjetaTxt
              p.mb-0 Si la compra es de urgencia, la fecha de entrega puede ser de inmediato; si la compra es programada, las fechas de entrega serán de acuerdo con un plan de recepción; todo esto bajo las condiciones de compra y de venta, las que se deben de respetar por parte del proveedor, so pena de no volver a surtir. 
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f3.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Fecha de pago
            .tarjetaTxt
              p.mb-0 Generalmente, esta se negocia si van a ser diferentes las condiciones de venta que nos da el proveedor, y puede ser a 45 días o a dos meses; debemos recordar que todas las facturas se pagan después de la presentación de la factura y, por lo general, se fecha a 30 días.
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f4.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Garantía
            .tarjetaTxt
              p.mb-0 El área de compras exige la garantía de calidad del proveedor, la que sin duda se cumple; pero hay ocasiones que se negocia una garantía mayor y, por lo general, también se cumple.
      .col-auto.mb-4
        .tarjeta.tarjeta-container.tarjeta-cyan
          .tarjetaContent
            .tarjetaImg
              figure.mb-3
                img(src="@/assets/curso/t8/f5.svg", alt="acceso", style="width:120px;").m-auto
              h5.text-center Lugar y hora de la recepción
            .tarjetaTxt
              p.mb-0 De acuerdo con las políticas de la empresa compradora, esta es la que impone hora y día para recepción de lo comprado; solo en casos de extrema urgencia, esta condición no se respeta.

    p.mb-5(data-aos="fade-right") Ahora conoceremos las concertaciones y alianzas con relación al precio:
    .row.justify-content-center.align-items-center
      .col-lg-10
        PasosA.color-acento-botones(tipo="n")(data-aos="fade-left")
          .row
            .col-auto
              p La concertación emerge entre el comprador y el proveedor, donde se definen las condiciones de la compraventa; entre estas condiciones se destacan:
              ul.lista-ul.fa-ul2
                li.mb-0
                  i.fas.fa-atom.cs
                  | Cantidad y especificaciones.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Precio.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Garantía.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Fecha de entrega.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Fecha de pago.
          .row
            .col-auto
              p.text-start Este convenio se establece por escrito; puede decirse que es un acuerdo entre comprador y vendedor, y donde se estipulan entre otras: 
              ul.lista-ul.fa-ul2
                li.mb-0
                  i.fas.fa-atom.cs
                  | La compraventa y el precio.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Las condiciones de pago.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Las condiciones de entrega y el lugar.
                li.mb-0
                  i.fas.fa-atom.cs
                  | La garantía.
                li.mb-0
                  i.fas.fa-atom.cs
                  | La cantidad de la compra.
          .row
            .col-auto
              p Para que este convenio tenga validez, se necesita: 
              ul.lista-ul.fa-ul2
                li.mb-0
                  i.fas.fa-atom.cs
                  | Esté firmado por un funcionario de la empresa y el proveedor o el vendedor.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Se realice conforme a la ley.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Se estipulen responsabilidades por ambos firmantes.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Se establezcan penalidades, si hay fallas en lo solicitado.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Otros acuerdos.
          .row
            .col-auto
              p.text-start Tipos de convenios de acuerdo con el precio: 
              ul.lista-ul.fa-ul2
                li.mb-0
                  i.fas.fa-atom.cs
                  | Precio.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Costo adicional.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Abierto.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Para cada artículo o por cada partida.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Adicional.
                li.mb-0
                  i.fas.fa-atom.cs
                  | Con entregas parciales y pagos por cada entrega.

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

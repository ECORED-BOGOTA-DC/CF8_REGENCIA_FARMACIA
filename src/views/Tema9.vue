<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 9
      h1 Catálogos de productos y servicios
    p(data-aos="fade-right") Este tipo de documentación contiene información sobre las especificaciones de los productos enlistados, así como sus precios, tiempos de entrega y/o lugares donde se pueden adquirir. Una gran desventaja que poseen los catálogos es que no se actualizan con la frecuencia ideal.
    .row
      .col-lg-6.mx-auto(data-aos="fade-left")
        .cajon.color-primario.p-4.mb-4
          p.mb-0 El valor de estos depende en gran parte de la forma en que se presentan los materiales que ofrecen y su utilización, así como sus características y especificaciones.
    p.mb-0(data-aos="fade-right") Existen catálogos de diferentes procedencias; entre ellos tenemos: de proveedores, de comisionistas y de maquinaria y/o equipo.
    Separador
    #t_9_1.titulo-segundo.color-acento-contenido
      h2 9.1 Métodos de clasificación de servicios y de producto
    .row.align-items-center(data-aos="fade-right")
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        img(src="@/assets/curso/t9/i1.png", style="width:400px", alt="Mujer aplicando crema en su mano").m-auto
      .col-lg-8(data-aos="fade-left")
        p.mb-4 La clasificación en la que el área de compras se debe basar es la siguiente:
        ul.lista-ul.fa-ul2
          li.mb-0
            i.fas.fa-atom.cs
            p <b>Materia prima y componentes:</b> cuando la empresa es manufacturera. 
          li.mb-0
            i.fas.fa-atom.cs
            p <b>Producto:</b> cuando la empresa es comercializadora.
          li.mb-0
            i.fas.fa-atom.cs
            p <b>Artículo:</b> conocido también como componente. 
          li.mb-0
            i.fas.fa-atom.cs
            p <b>Mercancía:</b> su razón principal es la de insumos, debido a que estos son usados en la fabricación o ensamble de los productos terminados de una empresa, aquellos que necesita la empresa para funcionar. 
    p.mb-0(data-aos="fade-right") Todos estos bienes son susceptibles de comprarse y provocan que se establezca una relación entre comprador y vendedor, en donde los dos personajes deben llevarse, a partes iguales, un beneficio.
    Separador
    #t_9_2.titulo-segundo.color-acento-contenido
      h2 9.2 Técnicas de estimación de precios
    p.mb-5(data-aos="fade-right") Según Sangri Coral, A. (2016 pp. 18-19), esta variable, en algunas ocasiones es la más importante; el precio, ya sea por unidad o por grandes volúmenes, debe ser #[strong “el precio exacto”] a fin que se efectúen las compras siguientes, y debe basarse en los siguientes términos:
    .row
      .col-lg-8.mb-4.mb-lg-0(data-aos="fade-right")
        AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--cac")
          .row(titulo="Que se pueda negociar")
            p El principal objetivo del área de compras es negociar el precio con relación a los tiempos de entrega y los mayores tiempos de pago. 
          .row(titulo="Que se conozcan los precios de la competencia ")
            p El área de compras debe conocer los precios de los productos de la competencia, para tomar la decisión y darle al proveedor la orden de compra o pedido, para lo cual se necesita, por lo menos, tener tres cotizaciones de los proveedores.
          .row(titulo="Que sean los normales o el de las ofertas ")
            p El precio nunca se debe aceptar con cambios; lo legal es que el proveedor siempre entregue el pedido con base al precio negociado en la orden de compra.
          .row(titulo="Que sea el del proveedor adecuado")
            p Para que el precio sea el acordado, no se debe cambiar al proveedor, ni pedirle a uno de ellos una cantidad y al otro, una diferente; puede haber diferencia en calidad y en precio y eso afecta el buen funcionamiento del área de compras. 
      .col-lg-4(data-aos="fade-left")
        img(src="@/assets/curso/t9/f1.svg", style="width:350px", alt="bolsa con medicamentos").m-auto

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

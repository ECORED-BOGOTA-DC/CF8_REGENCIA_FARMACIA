<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 7
      h1 Base de datos
    .row.traslape3.align-items-center.mb-5
      .col-lg-3.ms-auto.p-0(data-aos="fade-right")
        img(src='@/assets/curso/t7/i1.jpg', style="width:350px", alt='Mujer con libreta').m-auto
      .col-lg-4.p-5.fcp.fcp--mobile(data-aos="fade-left")
        .mt-3
        p Una base de datos es un sistema compuesto por un conjunto de datos y una serie de diferentes elementos que permiten organizar dichos datos utilizando diversas estructuras relacionadas, que permiten la manipulación y gestión de datos de forma rápida y fácil. Asimismo, la presentación de datos almacenados en bases de datos es un proceso sencillo que se puede realizar de diferentes y variadas maneras. En el ámbito empresarial, el uso de las bases de datos permite almacenar grandes cantidades de información sobre clientes, productos, proveedores y cualquier tipo de información.
      .col-lg-3.me-auto.p-0(data-aos="fade-down")
        img(src='@/assets/curso/t7/i2.jpg', style="width:350px", alt='Persona con medicamentos en la mano').m-auto
    p.mb-5(data-aos="fade-right") Existen diferentes tipos de bases de datos en función de los modelos de administración que se utilicen. Los más destacados por su amplia difusión y utilización son: 
    .row.align-items-center
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/t7/f1.svg', style="width:550px", alt='Personas con medicamentos').m-auto
      .col-lg-8(data-aos="fade-left")
        ul.lista-ul.fa-ul2
          li.mb-0
            i.fas.fa-atom.cs
            p Bases de datos jerárquicas.
          li.mb-0
            i.fas.fa-atom.cs
            p Bases de datos relacionales: son los modelos más utilizados en la actualidad.
          li.mb-0
            i.fas.fa-atom.cs
            p Bases de datos orientadas a objetos. 
        .bloque-texto-b.color-primario.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 Toda base de datos relacional cuenta con unas estructuras elementales para poder operar con los datos. Estas estructuras son las tablas, las consultas, los formularios y los informes.
            i.fas.fa-quote-right
            br
            br
            h6.text-right.d-flex.justify-content-end.mb-0 -López, G.M, 2015

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

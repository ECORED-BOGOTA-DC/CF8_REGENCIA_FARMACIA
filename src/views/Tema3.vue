<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Metodologías de programación
    p.mb-5(data-aos="fade-right") Partiendo de la lista de proveedores seleccionados, se procede a realizar la orden de compra que debe contener, como mínimo, los siguientes ítems:
    .row.align-items-center.mb-5.px-5
      .col-lg-4(data-aos="fade-right").mb-4.mb-lg-0
        img(src='@/assets/curso/t3/i1.png', style="width:350px" ,alt='Hombre con libreta en la mano').m-auto
      .col-lg-8.tarjeta--color-primario.borad1.p-5(data-aos="fade-left")
        ul.lista-ul.fa-ul2
          li.mb-0
            i.fas.fa-atom.cs
            p Nombre del producto exacto, es decir, en genérico o comercial y la concentración.
          li.mb-0
            i.fas.fa-atom.cs
            p Forma farmacéutica.
          li.mb-0
            i.fas.fa-atom.cs
            p Cantidad en unidades.
          li.mb-0
            i.fas.fa-atom.cs
            p Valor unitario.
          li.mb-0
            i.fas.fa-atom.cs
            p Valor total.
          li.mb-0
            i.fas.fa-atom.cs
            p Plazos de entrega.
          li.mb-0
            i.fas.fa-atom.cs
            p Condiciones de pago (plazos con descuento financiero y/o de pago neto).
          li.mb-0
            i.fas.fa-atom.cs
            p Condiciones especiales (marcación, entregas parciales, etc.)
    p.mb-0(data-aos="fade-right") Las órdenes de compra pueden ser físicas o digitales, y se deben guardar para luego compararlas con las facturas de venta cuando lleguen los pedidos.
    Separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Metodología de compras
    p.mb-5(data-aos="fade-right") Para un adecuado plan de compras, es necesario tener presente las siguientes variables que se sujeten a las necesidades de la institución.
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--purpuraMedio")(data-aos="fade-down")
      .row(titulo="Consumo promedio (CPM)")
        p Cantidad del medicamento o dispositivo médico que se consume en un periodo de días, semanas o meses, aunque por lo general se toman los datos de seis meses, arrojados de los consumos obtenidos, ya sea por consumo histórico o por perfil epidemiológico.
        .col-lg-4.mx-auto.mb-4
          img(src='@/assets/curso/t3/f5.svg', alt='CPM = Promedio consumo por período en meses / cantidad de período en meses', style="width:350px;").m-auto
        p <b>Ejemplo práctico:</b> se tienen los consumos de 6 meses de acetaminofén 500 mg tabletas.
        .col-lg-7.mx-auto.mb-4
          img(src='@/assets/curso/t3/f6.svg', alt='Ejemplo práctico')
        p <b>Nota:</b> cuando un periodo aparece en cero, ya sea porque el producto se encontraba agotado o por cualquier otra circunstancia, este no se tiene en cuenta. Ejemplo: de un periodo de seis meses, el mes cuatro se reporta en cero; al aplicar la fórmula, la cantidad de períodos sería de cinco, que son los que tienen datos.
      .row(titulo="Tiempo de reposición (TR)")
        .col-lg-2
          img(src='@/assets/curso/t3/f1.svg', alt='frasco de píldoras', style="width:250px;").m-auto
        .col-lg-10  
          p Representa el tiempo durante el cual se realizan todas las actividades propias de la compra, las cuales varían de acuerdo con la modalidad de compra y de los proveedores seleccionados. En algunos sistemas de salud, este periodo se duplica por los trámites administrativos. Este tiempo se toma desde la fecha en que se inicia la solicitud, hasta el momento en que se recibe el medicamento, en la respectiva dependencia (Unab, s.f.).
          p <b>Se debe establecer en fracción de tiempo expresado en meses.</b>
          p <b>Ejemplo práctico:</b> el TR es de 21 días
          p <b>Aplicando la fórmula:</b>
          .col-lg-2.mx-auto.mb-4
            img(src='@/assets/curso/t3/f7.svg', alt='TR = (21/30) * 0,7meses' , style="width:200px;").m-auto
      .row(titulo="Nivel mínimo de Existencias (NmE)")
        .col-lg-2
          img(src='@/assets/curso/t3/f2.svg', alt='brister',style="width:250px;").m-auto
        .col-lg-10  
          p Este cálculo representa la cantidad mínima suficiente de producto que debe existir en el inventario, mientras llega un nuevo pedido, con el fin de evitar agotamientos que generen demanda insatisfecha.
          p.text-center <b>NmE = CPM X TR (expresado en meses)</b>
          p <b>Ejemplo práctico: partiendo de los ejemplos anteriores, aplicamos la fórmula y tenemos que:</b>
          p.text-center <b>NmE = 152 x 0,7 = 106</b>
      .row(titulo="Nivel Máximo de Existencias (NME)")
        .col-lg-2
          img(src='@/assets/curso/t3/f3.svg', alt='frasco de píldoras', style="width:250px;").m-auto
        .col-lg-10
          p A diferencia del NmE, este cálculo representa la cantidad máxima de producto que debe haber en el inventario, con el fin de evitar que exceda el #[em stock] y comprometa los recursos financieros de la Institución.
          p.text-center <b>NME = CPM + (NmE x número de meses estimados para la compra)</b>
          p <b>Ejemplo práctico:</b> continuamos con los datos adquiridos en los puntos anteriores, teniendo presente que los meses estimados para la compra son un mes.
          p <b>Aplicando la fórmula:</b>
          p.text-center <b>NME = 152 + (106 x 1) = 262</b>
      .row(titulo="Punto de Reposición (PR)")
        .col-lg-2
          img(src='@/assets/curso/t3/f4.svg', alt='gotero y brister', style="width:250px;").m-auto
        .col-lg-10
          p Es la cantidad en existencia que realmente da inicio al proceso de compra. Es la relación entre la existencia de seguridad (NmE) y la demanda o consumo promedio mes (CPM), de un periodo en el cual pueda reponerse la existencia y alcanzar nuevamente un nivel de normalidad (Unab, s.f).
          p.text-center <b>Se puede expresar de dos formas:</b>
          p.text-center <b>PR = NmE + (CPM X TR)<br>PR = 2 X NmE</b>
          p.text-center <b>Aplicando la fórmula:</b>
          p.text-center <b>PR = 106 + (152 X 0,7) = 212<br>PR = 2 X 106 = 212</b>
    Separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Priorización de la compra
    .row.traslape3.align-items-center.mb-5
      .col-lg-3.ms-auto.p-0(data-aos="fade-right")
        img(src='@/assets/curso/t3/i2.jpg', style="width:350px", alt='brister').m-auto
      .col-lg-4.p-5.fcp.fcp--mobile(data-aos="fade-left")
        .mt-3
        p Existen diferentes metodologías para adquirir los productos farmacéuticos garantizando el cumplimiento de la cadena de suministros. 
        p Es importante tener presente que, en ocasiones, no es posible adquirir todos los productos por falta de presupuesto, lo que implica establecer prioridades al comprar y así obtener los productos más necesarios.
        p.mb-0 Para definir propiedades se cuenta con dos métodos:
      .col-lg-3.me-auto.p-0(data-aos="fade-down")
        img(src='@/assets/curso/t3/i3.jpg', style="width:350px" , alt='carrito con medicamentos').m-auto
    h3 Clasificación VEN
    p.mb-5 Esta clasificación se basa en la urgencia con la que se necesite un medicamento, de tal manera que nunca falten los productos vitales para los pacientes.
    .col-lg-8.mx-auto.noborad(data-aos="fade-right")
      .tarjeta-avatar-b.mb-5
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/ven-v.svg' alt='V')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p #[b Vitales]
            p.mb-0 Son medicamentos indispensables o vitales para la vida de los pacientes, como por ejemplo, oxígeno. Deben estar siempre disponibles, porque su escasez puede ocasionar graves consecuencias o incluso la muerte del paciente.
      .tarjeta-avatar-b.mb-5
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/ven-e.svg' alt='E')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p #[b Esenciales]
            p.mb-0 Su falta también puede ocasionar problemas graves a la salud o la muerte del paciente, pero con menor incidencia que los medicamentos anteriores. Normalmente hacen parte de este grupo, los productos para enfermedades como por ejemplo, los antihipertensivos.
      .tarjeta-avatar-b.mb-5
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/ven-n.svg' alt='N')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p #[b No esenciales]
            p.mb-0 Son medicamentos con baja frecuencia de uso, no son necesarios o vitales para la vida de los pacientes, por lo que su ausencia no significa agravar o generar problemas de salud. Ejemplo: suplementos dietarios.
    h3 Clasificación ABC o PARETO
    p.mb-5(data-aos="fade-right") Esta clasificación está basada en los costos de los productos. Es un acto de carácter administrativo, porque clasifica los productos por orden de inversión en: costosos, medianamente costosos y económicos, con el fin de reducir costos e incrementar la rentabilidad.
    .col-lg-8.mx-auto(data-aos="fade-right")
      .tarjeta-avatar-b.mb-4
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/abc-a.svg' alt='A')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p.mb-0 Estos productos son los más costosos en el inventario y se encuentran en menor cantidad, abarcando generalmente el 20 % del inventario.
      .tarjeta-avatar-b.mb-4
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/abc-b.svg' alt='B')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p.mb-0 Estos productos son menos costosos que los A y abarcan el 30 % del inventario.
      .tarjeta-avatar-b.mb-5
        .tarjeta-avatar-b__img
          img(src='@/assets/curso/t3/abc-c.svg' alt='C')
        .tarjeta.tarjeta--azul
          .py-5.px-4
            p.mb-0 Son los productos más económicos y abarcan el 50 % del total del inventario.
      .cajon.color-secundario.p-4
        p.mb-0 Cabe aclarar que la unión de ambos métodos da muy buenos resultados, tanto de inventario como de costos.

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

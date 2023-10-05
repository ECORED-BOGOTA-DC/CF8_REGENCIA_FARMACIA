<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.align-items-center
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
        p La selección y adquisición de medicamentos y dispositivos médicos dentro de un servicio o establecimiento farmacéutico necesarios para la promoción de la salud y prevención de la enfermedad, diagnóstico, tratamiento y recuperación de determinada enfermedad en cualquier paciente o usuario, conlleva una serie de actividades correlacionadas, que tienen como objetivo, garantizar la calidad de los medicamentos y dispositivos médicos en la cadena de abastecimiento. 
        p En el presente componente formativo, se realiza una detallada descripción de cada una de estas actividades, entre las que sobresalen las siguientes: 
        .cajon.color-secundario.p-4
          p.mb-0 Conformación del comité de farmacia y terapéutica y el comité de compras; definición del listado básico de medicamentos y dispositivos médicos; metodologías de programación, elaboración de base de datos, políticas de aprovisionamiento, fuentes de abastecimiento, políticas financieras y comerciales; determinación de proveedores y todo lo que esto conlleva y, finalmente, los procesos administrativos de planeación, organización, control y evaluación.
      .col-lg-5(data-aos="fade-left")
        img(src="@/assets/curso/if1.svg", style="width:450px" ,alt="Persona en dispensario de fármacos").m-auto
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>

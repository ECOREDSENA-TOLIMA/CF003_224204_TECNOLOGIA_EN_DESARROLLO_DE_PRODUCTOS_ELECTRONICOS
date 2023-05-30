<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    figure.mb-5(data-aos="fade")
      img(src="@/assets/curso/banner-intro.png", alt="Introducción")

    p(data-aos="fade") Dado que, en la actualidad, la electrónica se encuentra en muchas aplicaciones, nuevas tecnologías están siendo desarrolladas a un ritmo acelerado, tanto que su futuro parece ilimitado. Difícilmente podría señalarse un área de nuestras vidas, que no haya sido mejorada utilizando tecnología electrónica. Un capítulo importante en este tema está relacionado con el diagnóstico de estos dispositivos; y un aspecto a tener en cuenta allí es que un buen diagnóstico depende de las herramientas utilizadas, las cuales varían de acuerdo al caso a analizar. 
    p.mb-4(data-aos="fade") Una vez seleccionadas las herramientas a utilizar, se debe precisar dónde se van a aplicar y el saber interpretar correctamente los datos obtenidos; para esto, se debe tener claridad sobre las leyes, teoremas, principios y técnicas de análisis, cálculo y predicción del comportamiento de los circuitos, los elementos con los que se construyen circuitos, aparatos y máquinas eléctricas.

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-x.mb-5
          .bloque-texto-x__img
          .bloque-texto-x__contenido
            .bloque-texto-x__texto.p-4
              p La implementación de un buen diagnóstico depende en gran medida de poder tener, en lo posible, un área de trabajo en las mejores condiciones, pues se va a trabajar con electricidad, y esta requiere siempre de la aplicación de varios procedimientos y normas, todas ellas encaminadas a la protección de la vida y, en segundo plano, a la integridad de los equipos y herramientas. Adicional a ello, es necesario contar con un banco de trabajo que tenga las debidas protecciones eléctricas y aislamientos contra las descargas electrostáticas.

    .row.justify-content-center
      .col-lg-8(data-aos="fade-down")
        .cajon.color-primario.p-4.mb-4
          p Este contenido está orientado al diagnóstico de circuitos electrónicos, puntualmente a preparar áreas y equipos utilizados en el proceso, así como también a interpretar y elaborar la documentación necesaria para soportar el proceso.

    p(data-aos="fade") Para la elaboración de este componente, se abordaron varios autores conocidos en 
      strong.etiqueta diagnóstico de circuitos electrónicos, 
      | de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos del 
      strong.etiqueta desarrollo de productos electrónicos.

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
.bloque-texto-x
  display: flex
  &__img
    flex: 1 0 50%
    background-image: url(../assets/curso/intro-imagen.jpg)
    background-size: cover
  &__contenido
    background-color: $color-primario
    padding: 40px
    flex: 1 0 50%
  &__texto
    margin-left: -30%
    background-color: $white

  @media (max-width: $bp-max-md)
    flex-wrap: wrap
    &__img, &__contenido
      flex: 1 0 100%
    &__img
      padding-top: 62%
    &__contenido
      padding: 30px
    &__texto
      margin-left: 0
</style>

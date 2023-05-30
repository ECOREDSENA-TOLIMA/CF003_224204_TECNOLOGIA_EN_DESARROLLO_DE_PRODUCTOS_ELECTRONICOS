<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Insumos

    figure.mb-5(data-aos="fade")
      img(src="@/assets/curso/banner-tema3.png", alt="Insumos")  

    p.mb-4(data-aos="fade") Los insumos para electrónica son una pieza fundamental para el diagnóstico de circuitos electrónicos, sobre todo si la finalidad es la reparación. Es importante contar con un stock de elementos que permita el reemplazo de componentes averiados de manera inmediata. 

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-x
          .bloque-texto-x__img
          .bloque-texto-x__contenido
            .bloque-texto-x__texto.p-4
              p También es importante contar con insumos de consumo, como soldadura de estaño, pasta térmica y cintas aislantes.

    Separador


    // 3.1
    #t_3_1.titulo-segundo(data-aos="fade-right")
      .h2 3.1.  Tipos 

    p.mb-4(data-aos="fade") El siguiente gráfico ilustra los diferentes tipos de insumos utilizados en el diseño y diagnóstico de equipos electrónicos.

    .titulo-sexto.color-acento-contenido
      p.mb-0
        strong Figura 5. 
        | <em>Mapa mental con los diferentes tipos de insumos electrónicos</em>
    figure.mb-4
      img(src='@/assets/curso/tema3-1-fig5.svg', alt='Mapa mental con los diferentes tipos de insumos electrónicos')

    p(data-aos="fade") Dentro de los elementos electrónicos, es importante contar con un stock de los más comunes. Existe una amplia gama de estos componentes, por lo que casi siempre será necesario una orden de compra cuando se va a realizar un diagnóstico específico. A continuación, se presenta la clasificación de estos, para tener una idea aproximada de lo que se debe adquirir y tener siempre a la mano.

    Separador


    // 3.2
    #t_3_2.titulo-segundo(data-aos="fade-right")
      .h2 3.2.  Clasificación

    p.mb-4(data-aos="fade") Se pueden clasificar los insumos electrónicos de la siguiente manera:

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down") 
        .titulo-sexto.color-acento-contenido
          p.mb-0
            strong Figura 6. 
            | <em>Clasificación de insumos</em>
        PasosA.color-acento-contenido(tipo="n")
          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              h4 De consumo
              p A esta categoría pertenecen los elementos utilizados y desechados después de cierto tiempo, también los no reutilizables, como la soldadura de estaño, la pasta térmica, las cintas aislantes, las brocas, o los tornillos.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3-2-paso1.jpg', alt='Soldadura de estaño')
                figcaption.text-white Soldadura de estaño

          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema3-2-paso2.jpg', alt='Circuitos integrados')
                figcaption.text-white Circuitos integrados
            .col-md-6
              h4 Elementos  electrónicos
              p En esta categoría se encuentran los elementos propios de los módulos electrónicos, es decir, los ensamblados en las tarjetas que son susceptibles de sufrir daños y, por lo tanto, son reemplazables. Aquí encontramos los llamados 
                strong elementos pasivos, 
                | como los resistores, los condensadores, las bobinas o los inductores; es necesario tener un stock con los valores más comunes. También están los 
                strong elementos activos, 
                | tales como circuitos integrados análogos y digitales, transistores, diodos y tiristores.      

          .row.align-items-center
            .col-md-6.mb-4.mb-md-0
              h4 Elementos de protección
              p Es importante contar con estos elementos para el buen desarrollo de las actividades de diagnóstico. Durante el proceso de soldado y perforación es necesario proteger la vista.
            .col-md-6
              figure
                img(src='@/assets/curso/tema3-2-paso3.jpg', alt='Elementos de protección')

          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/tema3-2-paso4.jpg', alt='Insumos de corte')
                figcaption.text-white Insumos de corte
            .col-md-6
              h4 Insumos de corte
              p Estos insumos son necesarios, sobre todo, para reemplazo de componentes y desarrollo de prototipos. Aquí se encuentran las brocas, lijadoras y pulidoras. Se debe contar con varios de estos elementos y en diferentes tallas.

    Separador


    // 3.3
    #t_3_3.titulo-segundo(data-aos="fade-right")
      .h2 3.3.  Almacenamiento

    .row.mb-4
      .col-lg-7.mb-4(data-aos="fade-right")
        p Para el almacenamiento de insumos electrónicos, se deben tener en cuenta las características descritas en la etiqueta del producto o, en su defecto, los manuales técnicos. Algunos productos son sensibles a la humedad y, en el caso de las brocas, se oxidan y pierden el filo si son sometidas a los ambientes extremos. Los pines de los circuitos integrados, resistores y condensadores son sensibles a la oxidación, lo que dificulta su posterior fijación y soldado; muchos de ellos también son sensibles a las descargas electrostáticas, por lo que se debe tener especial cuidado en su almacenamiento y el uso necesario de esponjas y bolsas antiestáticas.
      .col-lg-5.mb-4(data-aos="fade-left")
        figure
          img.mb-2(src="@/assets/curso/tema3-3.jpg", alt="Almacenamiento")
          figcaption Nota. Tomada de ABC Pack (s. f.).

    .row.justify-content-center
      .col-lg-8
        .cajon.color-primario.p-4.mb-4
          p Los elementos sensibles a la electrostática no deben manipularse sin la debida protección contra este fenómeno. Debe usarse siempre manilla 
            strong antiestática.

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

<style lang="sass" scoped>
.bloque-texto-x
  display: flex
  &__img
    flex: 1 0 50%
    background-image: url(../assets/curso/tema3.jpg)
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

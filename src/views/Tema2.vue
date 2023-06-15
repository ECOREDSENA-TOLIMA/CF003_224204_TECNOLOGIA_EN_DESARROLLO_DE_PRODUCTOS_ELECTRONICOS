<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Herramientas y equipos

    figure.mb-5(data-aos="fade")
      img(src="@/assets/curso/banner-tema2.png", alt="Herramientas y equipos")
  
    p.mb-5(data-aos="fade") Un buen diagnóstico está ligado a contar y hacer buen uso de las herramientas para trabajos en equipos electrónicos. Revise, a continuación, lo correspondiente a las herramientas.

    .row.justify-content-center
      .col-lg-10
        .row 
          .col-lg-6.mb-4(data-aos="fade-right")
            .nav-holder
              img(src="@/assets/curso/tema2-hover1.png", alt="Herramientas")
              .text.p-lg-5.p-5.p-sm-3
                p Es posible encontrar en el comercio electrónico varios tipos de 
                  strong kits
                  | completos para esta labor. Esta imagen muestra  algunas de las herramientas necesarias para trabajar con equipos electrónicos.
          .col-lg-6.mb-4(data-aos="fade-left")
            .nav-holder(@mouseover="mostrarIndicador = false")
              .indicador--click(v-if="mostrarIndicador")
              img(src="@/assets/curso/tema2-hover2.png", alt="Osciloscopio digital")
              .text.p-lg-5.p-5.p-sm-3
                p Algunos equipos no son tan necesarios, pero facilitan el trabajo si se cuenta con ellos. Esta imagen presenta un equipo complementario: un microscopio y un osciloscopio digital.
    
    Separador


    // 2.1
    #t_2_1.titulo-segundo(data-aos="fade-right")
      .h2 2.1.  Tipos

    p.mb-5(data-aos="fade") Según el tipo de herramientas, se pueden encontrar:  electrónicas, manuales y herramientas inteligentes de diagnóstico. A continuación, se encuentra la diferenciación de las mismas.

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Herramientas electrónicas")
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2-1-tabs1.jpg', alt='Herramientas electrónicas')
          .col-md-1    
          .col-md-5
            h4 Herramientas electrónicas
            p Dentro de las herramientas electrónicas más comunes, se encuentran el multímetro digital y el osciloscopio. Estas herramientas complementan muy bien las  manuales, garantizando un buen diagnóstico. De estas dos, es imprescindible contar con el multímetro.
      .py-3.py-md-4(titulo="Herramientas manuales")
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2-1-tabs2.jpg', alt='Herramientas manuales')
          .col-md-1    
          .col-md-5
            h4 Herramientas manuales
            p Las herramientas manuales abarcan todos los elementos necesarios para acceder a los diferentes módulos de un equipo electrónico. Destornilladores, pinzas, alicates, sujetadores, extractores, cautín, levanta-pestaña, 
              strong protoboard, 
              | y un largo etcétera.
      .py-3.py-md-4(titulo="Herramientas inteligentes")
        .row.justify-content-center
          .col-md-4.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema2-1-tabs3.jpg', alt='Herramientas inteligentes')
              figcaption Tomada de Renishaw (2020).
          .col-md-1    
          .col-md-5
            h4 Herramientas inteligentes
            p Las herramientas inteligentes de diagnóstico son un tipo nuevo, que integra un poco de cada una de las ya mencionadas y se complementa con un 
              strong <em>software,</em> 
              | lo que permite el análisis de datos en tiempo real y así obtener un diagnóstico preciso y confiable.

    p.mb-4(data-aos="fade") Existen también las herramientas integradas. Estas están contenidas en un módulo conectado a un equipo de cómputo donde se visualizan todos los datos de medición. Este tipo de herramientas son muy útiles cuando se requiere hacer montaje de prototipos. Algunas de estas se presentan a continuación.

    .row.justify-content-center
      .col-lg-8
        .tarjeta--azul.p-4.mb-5
          SlyderA.slyder-tema2
            .row.px-lg-5
              figure.px-lg-5.py-lg-3
                img.m-2(src='@/assets/curso/tema2-1-slider1.jpg', alt='Dispositivo de laboratorio de ingeniería desarrollado para el aprendizaje basado en proyectos')
                figcaption Dispositivo de laboratorio de ingeniería desarrollado para el aprendizaje basado en proyectos. Nota. Tomada de NI (2020). 
            .row.px-lg-5
              figure.px-lg-5.py-lg-3
                img.m-2(src='@/assets/curso/tema2-1-slider2.jpg', alt='Captura de pantalla del software para Elvis III de National Instruments.')
                figcaption Captura de pantalla del software para Elvis III de National Instruments.

    Separador


    // 2.2
    #t_2_2.titulo-segundo(data-aos="fade-right")
      .h2 2.2.  Clasificación

    p.mb-5(data-aos="fade") En el siguiente mapa conceptual, se observa la clasificación de las herramientas utilizadas en el diagnóstico de equipos electrónicos.

    .titulo-sexto.color-acento-contenido
      p.mb-0
        strong Figura 4. 
        | <em>Clasificación de las herramientas para diagnóstico de equipos electrónicos</em>
    figure.mb-4
      img(src='@/assets/curso/tema2-2-fig4.svg', alt='Clasificación de las herramientas para diagnóstico de equipos electrónicos')

    p(data-aos="fade") Las herramientas utilizadas para el diagnóstico de equipos electrónicos generalmente son herramientas pequeñas. Un taller dedicado al diagnóstico electrónico requiere ciertos instrumentos y equipos que funcionen y hagan funcionar equipos con tensión de corriente continua. Además, se necesita de una cierta cantidad de herramientas manuales que no son muy comunes en otros tipos de talleres.

    p.mb-4(data-aos="fade") A continuación, se presentan algunas herramientas manuales y eléctricas


    h3.mb-4(data-aos="fade-right") Herramientas manuales
    TabsA.color-acento-contenido.mb-5(data-aos="fade-down")
      .tarjeta.color-tabs2-1-bg.p-4(titulo="Herramientas de corte")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-1.jpg', alt='Herramientas de corte')
          .col-md-6
            p Dentro de esta categoría, se encuentran herramientas como los alicates, utilizados más comúnmente para pelar y cortar cables.
      .tarjeta.color-tabs2-1-bg.p-4(titulo="Herramientas de sujeción")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-2.jpg', alt='Herramientas de sujeción')
          .col-md-6
            p También se encuentran los diferentes tipos de pinzas de sujeción y formado, utilizadas principalmente para ensamblar componentes.
      .tarjeta.color-tabs2-1-bg.p-4(titulo="Herramientas de fuerza")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-3.jpg', alt='Herramientas de fuerza')
          .col-md-6
            p Dentro de estas herramientas, es importante contar con un buen juego de destornilladores; estas son piezas fundamentales para las labores con equipos electrónicos. 
            p Existe una gama amplia de tornillos y nunca son suficientes los elementos con los que se cuenta para desarmar equipos. Se recomienda contar con varios juegos de diferentes tipos de destornilladores, siendo los más comunes los de tipo pala y estrella. Es común ver cómo diferentes marcas utilizan tipos específicos de tornillos, con el fin de que solo sus servicios técnicos autorizados puedan desarmar los equipos.
        .tarjeta.color-acento-contenido.px-4.py-3
          p.mb-0 Dentro del tipo de destornilladores especiales que se han hecho bastante comunes está el torx. Este tipo de tornillos aparece en muchas marcas de equipos electrónicos, incluyendo celulares, tabletas y PC portátiles.    
      .tarjeta.color-tabs2-1-bg.p-4(titulo="Herramientas de precisión")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-4.jpg', alt='Herramientas de precisión')
          .col-md-6
            p Otro aspecto a tener en cuenta a la hora de organizar unas buenas herramientas para diagnóstico es el proceso de medición. Si bien la medición de las variables electrónicas requiere de equipos especiales, también es necesario efectuar medidas comunes, como longitud, masa y temperatura, por lo que se hace necesario contar con algunas herramientas para este tipo de mediciones.
            p Es bueno contar con flexómetro, regla, termómetro y, en lo posible, con un pie de rey para mediciones más precisas.

    h3(data-aos="fade-right") Herramientas eléctricas
    p.mb-4(data-aos="fade") Se incluyen en este grupo las herramientas más comunes que requieren de la energía eléctrica para funcionar. 
    TabsA.color-secundario.mb-5(data-aos="fade-down")
      .tarjeta.color-tabs2-2-bg.p-4(titulo="Herramientas de medición")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-5.jpg', alt='Herramientas de medición')
          .col-md-6
            h5 Multímetro
            p Es imprescindible contar con un multímetro. Como su nombre lo indica, este permite realizar múltiples mediciones, siendo las más comunes: ohmios, tensión o voltaje, amperios, capacitancia e inductancia. Existen multímetros digitales y análogos.
      .tarjeta.color-tabs2-2-bg.p-4(titulo="Herramientas de perforación")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-6.jpg', alt='Herramientas de perforación')
          .col-md-6
            h5 Mototool
            p Es común contar en un taller con un mototool. Esta herramienta facilita muchas labores, siendo la más común la perforación.
      .tarjeta.color-tabs2-2-bg.p-4(titulo="Herramientas de fijación")
        .row
          .col-md-6.mb-4
            img(src='@/assets/curso/tema2-2-tabs-7.jpg', alt='Herramientas de fijación')
          .col-md-6
            h5 Cautín o pistola de soldar
            p Una herramienta fundamental para todo electrónico es el cautín o pistola de soldar. Esta herramienta permite fijar y retirar componentes electrónicos de los equipos, utilizando el calor para derretir el estaño.
            p Esta herramienta se puede complementar con una pistola de aire caliente. Esta permite fijar y retirar componentes de precisión y montaje superficial.   
    

    Separador


    // 2.3
    #t_2_3.titulo-segundo(data-aos="fade-right")
      .h2 2.3.  Características

    p(data-aos="fade") La principal característica de las herramientas para diagnóstico de equipos electrónicos es que deben contar con cierto grado de protección contra descargas eléctricas. Para ello, deben estar sujetos con la norma técnica que indique y garantice que están fabricadas para poder operar con tensión eléctrica.

    p.mb-4(data-aos="fade") Las herramientas se diseñan y fabrican para cumplir uno o más propósitos específicos, por lo que son artefactos con una función técnica; la mayoría de ellas son combinaciones de máquinas simples que proporcionan una ventaja mecánica. Cuando se trata de herramientas eléctricas, es importante verificar la etiqueta, para determinar la tensión de trabajo; este tipo de herramientas requiere especial cuidado, ya que siempre tiene integrado un motor que, de no ser manipulado con las protecciones debidas, puede ocasionar daños a la persona y al equipo.

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-x
          .bloque-texto-x__img
          .bloque-texto-x__contenido
            .bloque-texto-x__texto.p-4
              p Siempre que se trabaje con una herramienta de rotor, es importante utilizar los elementos de protección personal, como gafas y guantes. Para el cautín, se debe tener en cuenta cuál es la potencia de trabajo requerido. 



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    mostrarIndicador: true,
    modal1: false,
    mostrar1: false,
    mostrar2: false,
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
.nav-holder
  display: inline-block
  margin: 10px 5px
  overflow: hidden
  position: relative
  -webkit-transform: translateZ(0)
  -moz-transform: translateZ(0)
  transform: translateZ(0)
  border-bottom: 10px solid #00CCA7

.nav-holder *, .nav-holder *:before, .nav-holder *:after
  -webkit-box-sizing: border-box
  -moz-box-sizing: border-box
  box-sizing: border-box
  -webkit-transition: all 0.45s ease
  -moz-transition: all 0.45s ease
  transition: all 0.45s ease

.nav-holder:before
  position: absolute
  top: 0
  bottom: 0
  left: 0
  right: 0
  content: ''
  background-color: #00CCA7
  opacity: 0.7
  z-index: 888
  -webkit-transition: all 0.45s ease
  -moz-transition: all 0.45s ease
  -ms-transition: all 0.45s ease
  transition: all 0.45s ease
  border-top-left-radius: 15px
  border-top-right-radius: 15px

.nav-holder:before
  -webkit-transform: translateY(100%)
  -moz-transform: translateY(100%)
  transform: translateY(100%)

.nav-holder:hover:before
  -webkit-transform: translateY(0)
  -moz-transform: translateY(0)
  transform: translateY(0)
  opacity: 0.95
  -webkit-transition-delay: 0.1s
  -moz-transition-delay: 0.1s
  transition-delay: 0.1s

.nav-holder
  .text
    position: absolute
    top: 80%
    bottom: 0px
    left: 0px
    right: 0px
    z-index: 999
    bottom: 0
  img
    backface-visibility: hidden
    max-width: 100%
    vertical-align: top
    z-index: 0
  p
    margin: 0
    opacity: 0

.nav-holder .h4
  margin: 0
  opacity: 1

.nav-holder:hover
  .text
    top: 8%
  h4, p
    opacity: 1
    -webkit-transition-delay: 0.2s
    -moz-transition-delay: 0.2s
    transition-delay: 0.2s

.nav-holder a
  position: absolute
  top: 0
  bottom: 0
  left: 0
  right: 0
  z-index: 1

@media (max-width: $bp-max-lg)
  .nav-holder p
    font-size: 15px

// BLOQUE Imagen
.bloque-texto-x
  display: flex
  &__img
    flex: 1 0 50%
    background-image: url(../assets/curso/tema2-3.jpg)
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

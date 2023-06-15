<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Entorno de trabajo

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .bloque-texto-x
          .bloque-texto-x__img
          .bloque-texto-x__contenido
            .bloque-texto-x__texto.p-4
              p El entorno de trabajo es un aspecto muy importante a tener en cuenta cuando de hacer un buen diagnóstico se trata. Se deben considerar los posibles accidentes y enfermedades laborales que se puedan presentar, es el primer paso para evitarlos, de ahí la necesidad de aplicar las normas de seguridad y salud en el trabajo.
      
    Separador

    // 1.1
    #t_1_1.titulo-segundo(data-aos="fade-right")
      .h2 1.1.  Procedimientos de alistamiento del área de trabajo

    p.mb-5(data-aos="fade") Cuando se analiza el entorno de trabajo, es necesario pensar en lo que no se puede ver, ya que diversos aspectos pueden causar un accidente. La siguiente figura presenta algunos de estos puntos a considerar.  
  
    .row.justify-content-center.mb-4
      .col-lg-10(data-aos="fade-down")
        .titulo-sexto.color-acento-contenido
          p.mb-0
            strong Figura 1. 
            | <em>Aspectos que pueden causar un accidente</em>
        .slyder-tema1.row.justify-content-end
            .col-lg-10
              SlyderA.slyder-tema1-content.p-lg-5.p-3
                .row.justify-content-end.align-items-center.pb-4
                  .col-md-3.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema1-1-ico1.svg', alt='Aspectos que pueden causar un accidente')
                  .col-md-6
                    p.mb-0 Los accidentes con electricidad son de mucho cuidado, casi siempre están asociados a casos de incendio o descargas eléctricas al cuerpo humano.
                  .col-md-1
                .row.justify-content-end.align-items-center.pb-4
                  .col-md-3.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema1-1-ico2.svg', alt='Aspectos que pueden causar un accidente')
                  .col-md-6
                    p.mb-0 Es necesario evitar los cables cruzados por lugares de tránsito.
                  .col-md-1
                .row.justify-content-end.align-items-center.pb-4
                  .col-md-3.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema1-1-ico3.svg', alt='Aspectos que pueden causar un accidente')
                  .col-md-6
                    p.mb-0 Verificar tomas mal conectadas, dejando al descubierto contactos energizados.
                  .col-md-1
                .row.justify-content-end.align-items-center.pb-4
                  .col-md-3.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema1-1-ico4.svg', alt='Aspectos que pueden causar un accidente')
                  .col-md-6
                    p.mb-0 Se debe tener claro en qué casos se usan los elementos de protección contra cargas electrostáticas.
                  .col-md-1
                .row.justify-content-end.align-items-center.pb-4
                  .col-md-3.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/tema1-1-ico5.svg', alt='Aspectos que pueden causar un accidente')
                  .col-md-6
                    p.mb-0 El área debe estar bien ventilada, permitiendo la circulación de los vapores generados por el proceso de soldar; estos vapores contienen aleaciones de plomo, perjudiciales para la salud.
                  .col-md-1

    Separador


    // 1.2
    #t_1_2.titulo-segundo(data-aos="fade-right")
      .h2 1.2.  Normas de seguridad y salud en el trabajo

    .row.align-items-center
      .col-lg-5.mb-4(data-aos="fade-right")
        h4 La Resolución 5018 de 2019 expide los lineamientos de seguridad y salud en el trabajo para las actividades ejecutadas en los procesos de transformación de energía.
      .col-lg-7.mb-4(data-aos="fade-left")
        p Cuando se trabaja con equipos electrónicos, definitivamente, el mayor riesgo es sufrir una descarga eléctrica; dependiendo de la corriente recibida, esta descarga puede ser perjudicial para el cuerpo humano. A continuación, se presentan algunas normas de seguridad. Se invita a revisarlas.

    .row.justify-content-center.bg-color1.p-lg-5.p-1.mb-2
      .col-lg-8.col-12
        ImagenInfografica.color-secundario

          template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema1-2-figura1.svg', alt='Normas de seguridad y salud en el trabajo')


          .tarjeta.color-acento-contenido.p-3(x="-2%" y="74%")
            p Es obligatorio utilizar 
              strong zapatos dieléctricos. 
              | Estos evitan el contacto directo con la tierra, ya que a través de ella se genera la descarga eléctrica. En algunos casos, deben estar acompañados del uso de 
              strong guantes aislantes y gafas 
              | que protejan en caso de producirse una chispa.

          .tarjeta.color-acento-contenido.p-3(x="85%" y="8%")
            p No se deben llevar objetos de metal mientras se trabaja con electricidad: cadenas, relojes o anillos pueden ocasionar un cortocircuito o producir un arco eléctrico. El metal es un excelente conductor de la electricidad, por lo que, en caso de contacto, se produce una descarga muy peligrosa. Es necesario utilizar 
              strong ropa ajustada 
              | para evitar contactos y caídas.

          .tarjeta.color-acento-contenido.p-3(x="69%" y="34%")
            p Los equipos se deben trabajar, preferiblemente, sin suministro de energía. 
              strong Hay que evitar trabajar con electricidad en lugares húmedos o cerca de líquidos. 
              | Analizar el circuito, las conexiones, composición y las características del equipo antes de comenzar a trabajar, de esta manera se mide el peligro y se establecen las normas de seguridad.

          .tarjeta.color-acento-contenido.p-3(x="67%" y="96%")
            p Cuando se trabaja con la fuente de poder del equipo, en lo posible, se entra en contacto con los circuitos utilizando 
              strong una sola mano, 
              | ya que, si se utilizan las dos y se recibe una descarga, la corriente eléctrica pasa de una mano a la otra, afectando el corazón.

          .tarjeta.color-acento-contenido.p-3(x="18%" y="8%")
            p Las herramientas se deben usar de manera responsable. En la actualidad, existe todo tipo de materiales auxiliares. Sin embargo, en ocasiones se utilizan herramientas para fines para los que no están diseñadas. Se debe 
              strong utilizar un equipo completo de herramientas y sin correr riesgos.

          .tarjeta.color-acento-contenido.p-3(x="96%" y="73%")
            p En los talleres donde se trabaja con electricidad, es importante que se sigan, cumplan y respeten algunas normas de seguridad básicas para prevenir riesgos y accidentes. Estas son medidas que se deben seguir para  proteger la salud, mejorar la seguridad en los procesos productivos y anticipar accidentes o disminuir los riesgos laborales, minimizando peligros. Se recomienda siempre 
              strong usar equipos o herramientas adecuadas de protección personal o individual, 
              | como gafas, casco, botas, overol y guantes especiales, de acuerdo con la actividad que se desarrolle. Igualmente, la seguridad y la salud laboral son primordiales antes, durante y al finalizar cualquier práctica laboral o académica. Por tanto, se deben usar las herramientas pertinentes, de forma segura, en el taller o laboratorio.

    figcaption.mb-4 Nota. Tomada de Freepik.

    .row.align-items-center
      .col-lg-7.mb-4(data-aos="fade-right")
        p Ahora bien, en los talleres donde se trabaja con electricidad, es importante que se sigan, cumplan y respeten algunas normas de seguridad básicas para prevenir riesgos y accidentes. Estas son medidas que se deben seguir para proteger la salud, mejorar la seguridad en los procesos productivos y anticipar accidentes o disminuir los riesgos laborales minimizando peligros. 
        p Se recomienda 
          strong usar siempre equipos o herramientas adecuadas de protección personal o individual, como gafas, casco, botas, overol y guantes especiales, de acuerdo con la actividad que se desarrolle. 
          | Igualmente, la seguridad y la salud laboral son primordiales antes, durante y al finalizar cualquier práctica laboral o académica. Por tanto, se deben usar las herramientas pertinentes, de forma segura, en el taller o laboratorio.
      .col-lg-5.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema1-2-img1.jpg", alt="Imagen decorativa")

    p.mb-5(data-aos="fade") Entre estas normas básicas, se tienen las siguientes:

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        .titulo-sexto.color-acento-contenido
          p.mb-0
            strong Figura 2. 
            | <em>Normas básicas</em>
        .row
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico1.svg", alt="enchufe").m-auto
                .tarjetaTxt.text-white
                  p Evitar conectar equipos sin una revisión previa, esta es una de las normas de seguridad eléctrica más importantes. Por tanto, es mejor esperar unos minutos y no causar daños en equipos o personas.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2(@mouseover="mostrarIndicador = false", onclick="")
                .indicador--click(v-if="mostrarIndicador")
                .tarjetaContent
                  .tarjetaImg
                    figure
                      img(src="@/assets/curso/tema1-2-ico2.svg", alt="herramienta").m-auto
                  .tarjetaTxt.text-white
                    p Antes de empezar a trabajar con un equipo o herramienta, se debe revisar bien su estado y funcionamiento.

          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico3.svg", alt="guantes").m-auto
                .tarjetaTxt.text-white
                  p Usar las herramientas correctas o adecuadas en cada ocasión y los elementos de seguridad.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico4.svg", alt="Prohibido tomar").m-auto
                .tarjetaTxt.text-white
                  p Si ha tomado alguna droga, licor o medicamento que produzca somnolencia, no se debe trabajar con electricidad; pone en riesgo su vida y la de los demás.        

          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico5.svg", alt="No usar prendas mojadas").m-auto
                .tarjetaTxt.text-white
                  p No usar prendas mojadas. La humedad en el cuerpo aumenta la conductividad eléctrica, por lo tanto, hay mayor riesgo de daño.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico6.svg", alt="No usar accesorios").m-auto
                .tarjetaTxt.text-white
                  p No se deben usar cadenas, relojes, anillos, u otros objetos metálicos durante las actividades en el taller o laboratorio.

          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico7.svg", alt="soldador").m-auto
                .tarjetaTxt.text-white
                  p No dejar los cautines y pistolas de soldar cerca de cosas inflamables, pueden generar un incendio.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico8.svg", alt="circuitos eléctricos").m-auto
                .tarjetaTxt.text-white
                  p Verificar los circuitos eléctricos antes de conectarlos. En algunos casos, se pueden usar lámparas de prueba que limitan la corriente en caso de un cortocircuito.

          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico9.svg", alt="recoger cabello").m-auto
                .tarjetaTxt.text-white
                  p Cuando se está cerca de equipos de rotación, como motores, se debe recoger el cabello, ya que existe riesgo de quedar atrapado y sufrir lesiones.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico10.svg", alt="precaución").m-auto
                .tarjetaTxt.text-white
                  p Evaluar los riesgos que se pueden correr en el lugar de trabajo  y tomar las precauciones necesarias. Analizar su entorno no cuesta nada, no hacerlo puede ser muy costoso.

          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico11.svg", alt="Depositar las basuras").m-auto
                .tarjetaTxt.text-white
                  p Depositar las basuras en los lugares destinados para ello. Ser limpio y ordenado en el trabajo  ayuda a ser más eficiente.
          .col-lg-6.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico12.svg", alt="hidrante").m-auto
                .tarjetaTxt.text-white
                  p Ubique los dispositivos de seguridad, como extintores o hidrantes. Manténgalos disponibles y despejados para su rápido uso en caso de incendio o accidentes.

          .col-lg-12.mb-3
            .tarjeta.tarjeta-container.tarjeta-color2.tarjeta-grande
              .tarjetaContent
                .tarjetaImg
                  figure
                    img(src="@/assets/curso/tema1-2-ico13.svg", alt="evacuación").m-auto
                .tarjetaTxt.text-white
                  p En caso de un accidente, conserve la calma y evalué la situación, proteja su vida, verifique salidas de emergencia, personas en riesgo, tome prioridad por acciones que salven su vida o la de otras personas, avise a sus compañeros u organismos de emergencia, accione alarmas o realice llamada de emergencia en caso de no saber qué acción tomar. 
                             
    Separador


    // 1.3
    #t_1_3.titulo-segundo(data-aos="fade-right")
      .h2 1.3.  Condiciones técnicas, térmicas y atmosféricas que pueden influir según el tipo de equipo

    p.mb-5(data-aos="fade") Cuando se prepara una labor de diagnóstico de un equipo electrónico, hay muchos factores que pueden influir. 

    AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--gris" data-aos="fade-down")
      .row(titulo="Factores técnicos")
        .col-lg-11
          p Se debe tener especial cuidado con la alimentación eléctrica. Por ejemplo, es común intentar conectar un equipo a una toma diseñada para suministrar una tensión de 120 voltios y lo que realmente necesita es una con suministro de 220 voltios, pues algunos equipos diseñados para 220 v pueden funcionar, en cierta medida, en una toma de 120 v, pero solo con funciones limitadas.  
          p También se debe tener en cuenta la corriente suministrada por la toma eléctrica. Es posible que un equipo funcione en una toma de corriente particular, pero que, a la hora de trabajar a plena carga, el suministro de potencia no sea suficiente y esto introduce en errores en el diagnóstico. Se debe revisar el área de trabajo y tener certeza de que se cumplen todas las condiciones requeridas por el equipo al cual se le hará el diagnóstico. 
          p Es necesario revisar la etiqueta del equipo y, en caso de no poseerla, buscar en la hoja de vida o datos técnicos del fabricante. 

      div(titulo="Factores atmosféricos")
        .col-lg-11
          p En cuanto a las condiciones atmosféricas, estas deben ser tenidas muy en cuenta, ya que afectan de manera directa el buen funcionamiento de los equipos electrónicos. Las descargas eléctricas atmosféricas, siendo estas de tipo eléctrico, es natural pensar que van a incidir en un equipo electrónico.
          p En estas descargas, hay contenidas grandes cantidades de energía eléctrica que, de no ser canalizadas, destruirían de manera instantánea tanto al equipo como a quien se encuentre manipulándolo.          
          p Es importante contar con una buena puesta a tierra y las conexiones eléctricas como lo estipula la Resolución 9 0708 de agosto 30 de 2013, Reglamento Técnico de Instalaciones Eléctricas – RETIE -, la cual establece las medidas tendientes a garantizar la seguridad de las personas, de la vida tanto animal como vegetal y la preservación del medio ambiente, previniendo, minimizando o eliminando los riesgos de origen eléctrico, sin perjuicio del cumplimiento de las reglamentaciones civiles, mecánicas y fabricación de equipos.
          p.mb-4 Biegelmeier (1986)  estableció la relación entre el I2.t (energía específica) y los efectos fisiológicos.
        .row.justify-content-center
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              p.mb-0
                strong Tabla 1. 
                | Relación entre energía específica y efectos fisiológicos
            .tabla-b.color-acento-contenido.mb-5.p-1
              table
                caption Nota. Tomada de Biegelmeier (1986)
                thead.tabla-b__header
                  tr
                    td.column1 
                      h4.mb-0 Energía específica 
                        br
                        img(src="@/assets/curso/tema1-3-formula.svg", alt="Formula")
                    td.column2
                      h4.mb-0 Percepciones y reacciones fisiológicas
                tbody  
                  tr
                    td.text-center 4 a 8
                    td Sensaciones leves en dedos y en tendones de los pies.
                  tr
                    td.text-center 10 a 30
                    td Rigidez muscular suave en dedos, muñecas y codos.
                  tr
                    td.text-center 15 a 45
                    td Rigidez muscular suave en dedos, muñecas, codos y hombros. Sensación en las piernas.
                  tr
                    td.text-center 40 a 80
                    td Rigidez muscular y dolor en brazos y piernas.
                  tr
                    td.text-center 70 a 120
                    td Rigidez muscular y dolor, y ardor en brazos, hombros y piernas.


      div(titulo="Factores de humedad")
        .col-lg-11
          p También es importante tener en cuenta las condiciones de humedad y temperatura. En lugares muy secos, es normal que nuestro cuerpo se cargue de energía electrostática; este tipo de energía se almacena en nuestro cuerpo por la fricción y, al descargarse en el equipo, puede producir daños severos. 
          p En lugares muy húmedos, por el contrario, el cuerpo humano se vuelve más conductivo y el riesgo de descarga es para el operario. Se deben tener en cuenta las condiciones de temperatura en el etiquetado de los equipos; generalmente, se señala la temperatura ambiente máxima a la que opera el equipo. 
          p.mb-4 Los componentes electrónicos sufren daños severos si se sobrepasa su temperatura de funcionamiento, por eso es importante consultar la hoja de datos de los componentes electrónicos sobre los cuales se desea trabajar.
        .row.justify-content-center
          .col-lg-10
            .titulo-sexto.color-acento-contenido
              p.mb-0
                strong Figura 3. 
                | <em>Zonas corriente contra tiempo de exposición a los efectos de las corrientes alternas de 15 Hz a 100 Hz</em>
            .row
              .col-lg-6
                figure
                  img(src="@/assets/curso/tema1-3-figura3-1.svg", alt="Zonas corriente contra tiempo de exposición a los efectos de las corrientes alternas de 15 Hz a 100 Hz")
              .col-lg-6   
                figure
                  img(src="@/assets/curso/tema1-3-figura3-2.svg", alt="Zonas corriente contra tiempo de exposición a los efectos de las corrientes alternas de 15 Hz a 100 Hz") 


    Separador


    // 1.4
    #t_1_4.titulo-segundo(data-aos="fade-right")
      .h2 1.4.  Procedimientos de aprovisionamiento y solicitud

    .row
      .col-lg-7.mb-4(data-aos="fade-right")
        p Lo primero que se debe tener en cuenta para un buen aprovisionamiento de elementos y herramientas electrónicas es establecer necesidades reales. Se debe tener un listado de los elementos más comunes, y un paso importante antes de solicitar la orden de compra es justificar la adquisición del mismo.
        p Es una buena práctica buscar cotizaciones de diferentes marcas y presentarlas con la solicitud de compra. Esto permite establecer un presupuesto y viabiliza la adquisición. Asimismo, clasificar los insumos, para tener una idea clara de lo que se necesita comprar.
      .col-lg-5.mb-4(data-aos="fade-left")
        img(src="@/assets/curso/tema1-4-img1.jpg", alt="Imagen decorativa")



</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    mostrarIndicador: true,
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
    background-image: url(../assets/curso/tema1-imagen.jpg)
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

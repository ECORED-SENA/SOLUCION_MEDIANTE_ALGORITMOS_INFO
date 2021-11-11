<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Solución de problemas mediante la utilización de algoritmos
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Solución de problemas mediante la utilización de algoritmos
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 21710101
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 96
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 8 Semanas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              
        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/U8RvbmiZKcs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p 
      strong Bienvenido apreciado aprendiz.

    p El programa Solución de problemas mediante la utilización de algoritmos, profundiza en el mundo de los algoritmos desde el pensamiento algorítmico, pasando por la solución de problemas y llegando a la programación. Paso a paso y de forma práctica, aprendiendo de diagramas de flujo, pseudocódigo, y el  diseño de un algoritmo de manera efectiva.
    p Hoy en día el mundo entero está digitalizado, hay un sentido de inteligencia y de comunicación en cada dispositivo  esto hace que nuestras vidas sean tan fáciles y rápidas. Todos estos avances tecnológicos son impulsados por software, que es un grupo de programas destinados a resolver un problema y cada programa se basa en una lógica, que se denomina algoritmo.
    p Un algoritmo se puede definir como un procedimiento que nos indica los pasos para  solucionar un problema. En el mundo de la programación, un algoritmo  es un conjunto de reglas que le indican a la computadora cómo realizar una tarea.
    p Antes de aprender un lenguaje de programación o de desarrollar un programa, se debe conocer la forma de resolver los problemas, entender cómo se espera que se desglose y analizar los caminos de la solución.
    p Los algoritmos son un entrenamiento que se debe entender y practicar para después lograr con la programación, compartir la solución a un computador o software y que éste la ejecute.
    p El SENA ofrece este programa con todos los elementos de formación, con una metodología de aprendizaje innovadora, que permitirá conocer y aprender todo sobre los algoritmos que son el camino al éxito a la hora de programar. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p El software ha demostrado recientemente la importancia que tiene en el sector productivo y en la vida de las personas de todo el mundo, además de la creciente participación global en el entorno digital, esto repercute en el desarrollo de actividades en todos los sectores. 
    p  El número de profesionales de tecnología que demandan las empresas colombianas es mucho mayor que el de profesionales disponibles en el país, según datos del Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC). El déficit de profesionales en esa área será de casi 70 mil cerrando el 2019. Dadas las proyecciones, después de 2019 el problema de la escasez de talento humano formado en áreas de TI, seguirá creciendo y no puede resolverse fácilmente, por lo tanto, el Gobierno de Colombia debe adoptar medidas para superar este déficit. Ante la necesidad existente y futura de formación de personal en tecnologías relacionadas con el sector de las TIC, se deben ofertar programas de formación para el fortalecimiento de capacidades en desarrollos a la medida, programación, algoritmos, bases de datos y redes. 
    p  Estos campos requeridos de formación están siendo demandados por el sector productivo y generan oportunidades potenciales de desempeño para las personas, derivando en los factores que se tienen en cuenta para la generación de diseños curriculares relacionados con las tecnologías del sector TIC y la red de conocimiento en informática, diseño y desarrollo de software, como apoyo al crecimiento de este. 
    p  De acuerdo con cifras del observatorio laboral y ocupacional colombiano en el cuarto trimestre 2020 se evidenció en la ocupación analistas de sistemas informáticos, la relación entre buscadores de empleo según situación ocupacional de: 88.1 % de aspirantes, 7.2 % de cesantes y 4.7 %. ocupado.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    ul.lista-ul
      li 
        i.fas.fa-circle
        | Crear algoritmos para solución de problemas.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    ul.lista-ul
      li 
        i.fas.fa-circle
        | Conocimientos básicos en Ofimática (Internet y Redes Sociales).     
      li 
        i.fas.fa-circle
        | Nociones de operaciones matemáticas y lógicas. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
    ul.lista-ul.px-4
      li 
        i.fas.fa-circle
        | Dinámica de grupos.   
      li 
        i.fas.fa-circle
        | Técnicas participativas.
      li 
        i.fas.fa-circle
        | Solución de problemas.  

    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul.px-4
      li 
        i.fas.fa-circle
        | El instructor – Tutor.  
      li 
        i.fas.fa-circle
        | El entorno.
      li 
        i.fas.fa-circle
        | Las TIC.
      li 
        i.fas.fa-circle
        | El trabajo colaborativo.          




  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>

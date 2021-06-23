<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span  5
      h1 Planeación, diseño y herramientas para la creación de un video
    p.mb-5  El video es un contenido muy completo que permite grandes posibilidades; es por esta razón que es vital tener en cuenta los aspectos vistos anteriormente en la planeación del contenido.
    .row.mb-5
      .col-lg-7
        p.mb-4  El video contiene imágenes en movimiento o estáticas y, normalmente, va acompañado de un audio. Por tal motivo, uno de los componentes importantes a construir es un guion, el cual incluye contenido de audio y de imágenes como si fuera una historieta, a lo que se le conoce como storyboard.
        p.mb-4  Es importante tener en cuenta cómo va a ser la comunicación corporal, o no verbal, dentro de la grabación del video y al ser este un factor a planear, se puede incluir en el storyboard.
        p.mb-4  El rostro, el movimiento del cuerpo en conjunto con los componentes de la voz, se articulan para que el video transmita emociones; por eso la importancia de poder incluir todo esto en el storyboard, el cual se conoce como el entregable del diseño del video.
        p.mb-4  Grabar y editar videos se ha convertido en una tarea aparentemente fácil, desde el uso de los teléfonos inteligentes; pero cuando se pretende producir un video con aspecto profesional, es importante atender algunas recomendaciones, las cuales se pueden analizar en el video “Tutorial para grabar videos desde la casa con el celular (Smartphone)” haciendo clic en el enlace.
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> Tutorial para grabar videos desde la casa con el celular. 


      .col-lg-5
        figure.mb-4
          img(src='@/assets/curso/t5-i1.svg', alt='Texto que describa la imagen')

    p.mb-5  Múltiples soluciones para edición de video se encuentran en la red, y estas permiten combinar textos, imágenes y audios en un solo contenido. Pero, para lograr un buen video, es necesario tener una planeación adecuada donde:
    TabsA.color-acento-botones.mb-5
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.color-acento-botones--borde.p-4(titulo="Paso 1: Guion")
        h4 Paso 1: Guion
        p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
          strong user style sheets
          |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
        p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.color-acento-botones--borde.p-4(titulo="Paso 2: Escenario")
        h4 Paso 2: Escenario

        .row
          .col-xl-6.mb-4
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen
          .col-xl-6
            p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
              strong user style sheets
              |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.color-acento-botones--borde.p-4(titulo="Paso 3: Grabación")
        h4 Paso 3: Grabación
        p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
          strong user style sheets
          |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
        p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.color-acento-botones--borde.p-4(titulo="Paso 4: Edición")
        h4 Paso 4: Edición
        p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
          strong user style sheets
          |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
        p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      
      //- .tarjeta debe ir acompañado de una de una de estas clases => 
      //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
      //- estas clases tambien tienen un modificador --borde
      .tarjeta.color-acento-botones--borde.p-4(titulo="Paso 5: Exportar el video")
        h4 Paso 5: Exportar el video
        p This is a normal paragraph (<code>p</code> element). To add some length to it, let us mention that this page was primarily written for testing the effect of 
          strong user style sheets
          |. You can use it for various other purposes as well, like just checking how your browser displays various HTML elements by default. It can also be useful when testing conversions from HTML format to other formats, since some elements can go wrong then.
        p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
      

    
    //- El componente "Muestras" tiene las aplicaciones de todos los componentes de la base
    //- se encuentra en src/components/Muestras.vue
    //- Una vez el componente "Muestras" no se necesite 
    //- Se debe borrar el "import Muestras from '../components/Muestras'" y en "components" en "<script"
    //- esto evitará que se compile en la carpeta final de distribución
    Muestras
</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema5',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>

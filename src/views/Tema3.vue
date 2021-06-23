<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span  3
      h1 Planeación, diseño y herramientas para elaborar presentaciones
    .row.mb-5
      .col-lg-8
        p.mb-4.text-bold  ¿Sabías que la presentación es una herramienta importante cuando se va a socializar?
        p.mb-4  Uno de los aspectos más importantes es que contenga gráficos, porque ellos representan metáforas y son fundamentales para el cerebro humano.
        p.mb-4  El texto debe ser limitado de manera esencial y contrastar con el color del fondo. La letra negra en un fondo oscuro no se va a poder ver; lo mismo pasa con un fondo pastel con letra blanca.
        p.mb-4  Teniendo en cuenta todo lo anterior, se deben considerar <b>los siguientes puntos en el diseño de las diapositivas para las presentaciones:</b>
        .row
          .col-lg-10.offset-lg-1
            ul.lista-ul
              li 
                i.fas.fa-angle-right
                | Tener en mente el tiempo con el que se cuenta para la presentación y decidir cuántas diapositivas se van a utilizar.
              li 
                i.fas.fa-angle-right
                | Realizar un esquema de tiempo y de temas, especificando cuánto tiempo se toma para cada diapositiva.
              li 
                i.fas.fa-angle-right
                | Como ya se definieron previamente la secuencia y las imágenes a utilizar, es importante ir organizando la forma como se quiere que las imágenes sean observadas y el lugar donde irán los textos y las modificaciones a los ángulos de las imágenes y otros detalles.
              li 
                i.fas.fa-angle-right
                | Realizar un guion base con palabras clave y visualizar cada diapositiva para articular el discurso con el recurso.
              li 
                i.fas.fa-angle-right
                | Pasar a la fase de construcción final, ensayo y ajustes.

      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t3-i1.svg', alt='Texto que describa la imagen')

    p.mb-5  Es importante aclarar que se pueden buscar plantillas gratuitas, identificando en cuáles se debe dar reconocimiento al diseñador de la plantilla y usarlas de manera efectiva en los ajustes.
    .row.justify-content-center.mb-5
      .col-lg-10
        .cajon.color-primario.p-4
          p <b>Recuerda:</b> para crear una presentación efectiva, se requiere ser cuidadoso al momento <b>de elegir los elementos visuales, el tipo de fuente y el punto focal.</b> Si se tienen en cuenta estos 3 elementos en lo que se quiere comunicar, se estará más cerca de lograr lo que se desea.
    p.mb-5  El siguiente listado contiene algunas de las plataformas que permiten <b>crear presentaciones interactivas online, de manera gratuita o a través de un registro:</b>

    .row.justify-content-center.mb-5
      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i2.svg', alt='Texto que describa la imagen')
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> www.canva.com

      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i3.svg', alt='Texto que describa la imagen')
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> https://prezi.com
      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i4.svg', alt='Texto que describa la imagen')
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> www.emaze.com
    .row.justify-content-center.mb-5
      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i5.svg', alt='Texto que describa la imagen')
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> www.powtoon.com

      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i6.svg', alt='Texto que describa la imagen')
        a.anexo.mb-4.mb-lg-0(href="#!" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-link.svg")
          .anexo__texto
            p <b>Enlace web.</b> www.slidebean.com
    p.mb-5  Al igual que con la planeación de una imagen, es importante considerar los siguientes puntos:
    .row 
      .col-lg-3
        figure.mb-4
          img(src='@/assets/curso/t3-i7.svg', alt='Texto que describa la imagen')
      .col-lg-9
        ul.lista-ul
          li 
            i.fas.fa-angle-right
            | Definir lo que se quiere comunicar.
          li 
            i.fas.fa-angle-right
            | Examinar la herramienta y sus posibilidades antes de empezar.
          li 
            i.fas.fa-angle-right
            | Definir los datos relevantes que se van a exponer en cada página o diapositiva.
          li 
            i.fas.fa-angle-right
            | Crear una secuencia de la información para que contenga un hilo conductor.
          li 
            i.fas.fa-angle-right
            | Realizar el diseño de la presentación.      
          li 
            i.fas.fa-angle-right
            | Elegir imágenes y fuentes en armonía con los colores.
          li 
            i.fas.fa-angle-right
            | Construir la presentación, revisarla y ensayarla.    
    

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>

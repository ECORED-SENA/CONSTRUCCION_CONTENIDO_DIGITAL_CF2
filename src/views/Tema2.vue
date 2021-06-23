<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span  2
      h1 Herramientas para la construcción de una imagen
    p.mb-5  Las herramientas para la creación de imágenes, brindan una gama alta de posibilidades de edición en cuanto a filtros, fuentes de texto, formas, entre otras. Existen múltiples herramientas en el mercado, algunas gratuitas y otras pagas y, con respecto al sistema operativo, se pueden encontrar online algunas como por ejemplo:
    .row.justify-content-center.mb-4
      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i1.svg', alt='Texto que describa la imagen')
        .h4 Figma
        p.mb-3
          Es un editor de gráficos, vectorial, y una herramienta de generación de prototipos, basada principalmente en la web, con características off-line adicionales, habilitadas por aplicaciones de escritorio en macOS y Windows.

      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i2.svg', alt='Texto que describa la imagen')
        .h4 Canva
        p.mb-3 Es Fundado en 2012, es un software y un sitio web de herramientas de diseño gráfico simplificado. Utiliza un formato de arrastrar y soltar, y proporciona acceso a más de 60 millones de fotografías y 5 millones de vectores, gráficos y fuentes.
    .row.justify-content-center.mb-5
      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i3.svg', alt='Texto que describa la imagen')
        .h4 Gimp
        p.mb-3  Es un programa de edición de imágenes digitales, en forma de mapa de bits, tanto de dibujos como de fotografías. Es un programa libre y gratuito.

      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i4.svg', alt='Texto que describa la imagen')
        .h4 Pixlr
        p.mb-3  Es un conjunto de herramientas y utilidades de imágenes, basado en la nube, que incluye varios editores de fotografías y un servicio para compartirlas.
    .row
      .col-lg-7
        p.mb-4  En algunas de las herramientas mencionadas o en la de su preferencia, se puede editar una imagen en el celular o en la tablet; pero antes de hacerlo, es importante tener en cuenta lo que veremos a continuación, <b>para poder crear una imagen con contenido útil o, si es el caso, atraer a los clientes:</b>
        ol.lista-ul
          li 
            i.fas.fa-angle-right
            | Definir lo que se quiere comunicar.
          li 
            i.fas.fa-angle-right
            | Examinar la herramienta y sus posibilidades antes de empezar.
          li 
            i.fas.fa-angle-right
            | Elegir las fotografías que se van a utilizar.
          li 
            i.fas.fa-angle-right
            | Diseño de la imagen.
          li 
            i.fas.fa-angle-right
            | Construir la imagen.
          
      .col-lg-5
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i5.svg', alt='Texto que describa la imagen')    
    p.mb-3  Aparte de las herramientas que nos permiten construir la pieza gráfica, se requieren recursos adicionales como imágenes, vectores, fuentes, entre otros, <b>los cuales nos permiten cumplir con el objetivo que las piezas quieren transmitir.</b>
    p.mb-5  Algunos recursos valiosos que podemos encontrar en la web, <b>los cuales son libres de derechos y podemos usar sin inconvenientes,</b> son:

    h4.mb-5 Bancos de imágenes
    .row.justify-content-center.mb-4
      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i6.svg', alt='Texto que describa la imagen')
        .h4 Figma
        p.mb-3
          Es un editor de gráficos, vectorial, y una herramienta de generación de prototipos, basada principalmente en la web, con características off-line adicionales, habilitadas por aplicaciones de escritorio en macOS y Windows.

      .col-lg-4
        figure.mb-4
          img.h100(src='@/assets/curso/t2-i7.svg', alt='Texto que describa la imagen')
        .h4 Canva
        p.mb-3 Es Fundado en 2012, es un software y un sitio web de herramientas de diseño gráfico simplificado. Utiliza un formato de arrastrar y soltar, y proporciona acceso a más de 60 millones de fotografías y 5 millones de vectores, gráficos y fuentes.



</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>

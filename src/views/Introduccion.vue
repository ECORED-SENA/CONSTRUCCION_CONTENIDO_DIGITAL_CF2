<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row
      .col-lg-7
        p.mb-3  Se denomina contenidos digitales, a toda la información que se encuentra incorporada en un medio digital.  Se hallan en páginas web, en redes sociales o en cualquier rincón de Internet.
        p.mb-3  Estos contenidos pueden estar conformados por imágenes, textos, videos, o muchos elementos más; <b>recuerda que la creatividad no tiene límites.</b>
        p.mb-3  Pero siempre hay que tener en cuenta que: el contenido de calidad es uno de los pilares esenciales de cualquier proyecto digital. Es por esta razón que en este componente formativo aprenderemos sobre la planeación, diseño y principales herramientas que se utilizan para la elaboración de imágenes, presentaciones, audios y videos.
        p.mb-3.text-bold  ¡Muchos éxitos en este aprendizaje! 
      .col-lg-5
        figure.mb-5
          img(src="@/assets/curso/t0-i1.svg", alt="imagen decorativa relacionada a computacion, documentos y medios digitales")


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

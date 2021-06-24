<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span  1
      h1 Diseño y concepto de piezas gráficas
    .row.mb-5
      .col-lg-8
        p.mb-3  El término diseño es muy utilizado a nivel general; por ejemplo, cuando alguien quiere construir una casa, uno de los pasos iniciales es el diseño, o cuando se habla de una propuesta en un proyecto o una empresa, se planea y se diseña antes de ejecutarla.
        p.mb-3  Diseñar es fundamental para lograr objetivos y tener una idea más clara de lo que se quiere obtener. <b>En el mundo del contenido digital, es fundamental elaborarlo para poder ejecutar acciones conformes con ese diseño y con los requerimientos expuestos.</b>
        p.mb-3  Te invitamos a ver el siguiente video, el cual presenta algunas reglas básicas que se deben tener en cuenta en el momento de realizar las piezas gráficas.
      .col-lg-4
        figure.mb-5
          img(src="@/assets/curso/t1-i1.jpg", alt="Escritorio y Pantalla de computador ejecutando un software para edición gráfica")

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
    p.mb-5  Teniendo claras algunas reglas que permiten determinar la estética de una pieza gráfica, es importante que estudiemos el flujo de trabajo recomendado para la creación de piezas gráficas.
    
    .row.justify-content-center
      .col-lg-10
        PasosA.color-primario.mb-5(tipo="n")
          .row
            .col-md-2
              figure
                img.h100(src='@/assets/curso/t1-i2.svg', alt='Texto que describa la imagen')
            .col-md-10.mb-4.mb-md-0
              h4 Definir lo que se quiere
              p Definir si la imagen se va a publicar en Facebook como portada de una página, en un tweet, o como miniatura de un video en YouTube, Instagram o en algún dispositivo móvil. Es importante tener esto en cuenta, porque las imágenes de portada son rectangulares, mientras que las miniaturas de videos o las imágenes en Instagram, son cuadradas.
            


          .row
            .col-md-10
              h4 Generar ideas
              p Se escriben las ideas que se tienen sobre el contenido de la imagen, lo que se consideraque  debe aparecer, si es necesaria alguna foto o si se necesitan recursos ya creados para ser buscados por Internet y anexarlos a la imagen. Todo esto, pensando siempre en la idea que se quiere potenciar.

            .col-md-2.mb-4.mb-md-0
              figure
                img.h100(src='@/assets/curso/t1-i2-1.svg', alt='Texto que describa la imagen')

              

          .row
            .col-md-2
              figure
                img.h100(src='@/assets/curso/t1-i3.svg', alt='Texto que describa la imagen')

            .col-md-10.mb-4.mb-md-0
              h4 Crear bocetos
              p Crear dibujos preliminares realizados rápidamente y sin tanta complejidad. Se recomienda tener en cuenta colores, textos y demás elementos que harán parte de la imagen a crear. Puede trabajarse en papel o utilizar programas como CANVA, el cual se vio en el apartado de planeación.
          


          .row
            .col-md-10.mb-4.mb-md-0
              h4 Validación
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          
            .col-md-2
              figure
                img.h100(src='@/assets/curso/t1-i4.svg', alt='Texto que describa la imagen')

          .row
            .col-md-2
              figure
                img.h100(src='@/assets/curso/t1-i5.svg', alt='Texto que describa la imagen')

            .col-md-10.mb-4.mb-md-0
              h4 Boceto final
              p Aquí va la representación más cercana al producto que se va a construir para empezar el proceso.
          







  
</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.h100{height: 100px}
</style>

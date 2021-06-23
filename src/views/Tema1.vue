<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span  1
      h1 Diseño y concepto de piezas gráficas
    .row.mb-5
      .col-lg-7
        p.mb-3  El término diseño es muy utilizado a nivel general; por ejemplo, cuando alguien quiere construir una casa, uno de los pasos iniciales es el diseño, o cuando se habla de una propuesta en un proyecto o una empresa, se planea y se diseña antes de ejecutarla.
        p.mb-3  Diseñar es fundamental para lograr objetivos y tener una idea más clara de lo que se quiere obtener. <b>En el mundo del contenido digital, es fundamental elaborarlo para poder ejecutar acciones conformes con ese diseño y con los requerimientos expuestos.</b>
        p.mb-3  Te invitamos a ver el siguiente video, el cual presenta algunas reglas básicas que se deben tener en cuenta en el momento de realizar las piezas gráficas.
      .col-lg-5
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
            .col-md-6.mb-4.mb-md-0
              h3 Definir lo que se quiere
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
            .col-md-6
              figure
                img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
                figcaption Leyenda de la imagen

          .row
            .col-md-6.mb-4.mb-md-0
              figure
                img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
                figcaption Leyenda de la Imagen
            .col-md-6
              h3 Nullam vulputate mauris eros, ut.
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
              

          .row
            .col-md-6.mb-4.mb-md-0
              h3 Duis laoreet est non ligula.
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          
            .col-md-6
              figure
                img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
                figcaption Leyenda de la imagen

          .row
            .col-md-6.mb-4.mb-md-0
              h3 Duis laoreet est non ligula.
              p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
          
            .col-md-6
              figure
                img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
                figcaption Leyenda de la imagen













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
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>

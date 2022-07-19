<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 7
      h1 Slider de imágenes

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/sliders/Slider.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 El Slider de imágenes es un componente web que permite mostrar de manera secuencial múltiples imágenes y textos. En algunos casos se puede hacer uso de componentes interactivos sencillos dentro de cada una de las diapositivas.

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - slider de imágenes
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de sliders de imágenes. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 

    .row
      .col-lg-12.order-2.order-lg-1
        TabsA.color-acento-botones       
          .tarjeta.clr--gris.p-4(titulo="Requerimientos de información")
            ul.lista-ul.mb-0
              li 
                i.fas.fa-angle-right.txt--orange
                | Titulo corto e ilustrativo (cuando aplica).
              li 
                i.fas.fa-angle-right.txt--orange
                | Cada diapositiva debe ir acompañada de un texto corto que acompañe a una  foto o ilustración.

           

    separador

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados    

    .bg--gradientBlue.p-5.mb-4
      SlyderB(:datos="datosSlyder")
   

</template>

<script>
export default {
  name: 'Tema7',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Histograma',
        texto:
          'Agrupación de datos.<br>Sirve para datos cualitativos y cuantitativos.<br>Las barras siempre van unidas.<br>Los histogramas ayudan a ver el centro, la extensión y la forma de un conjunto de datos.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_01.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Polígono de frecuencia',
        texto:
          'Gráfico que se crea a partir de un histograma de frecuencia. Estos histogramas emplean columnas verticales para reflejar frecuencias: el polígono de frecuencia es realizado uniendo los puntos de mayor altura de estas columnas.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_02.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Diagrama de barras',
        texto:
          'Un diagrama de barras es una representación en dos dimensiones de la frecuencia, ya sea absoluta o relativa, de una variable cuantitativa o cualitativa, pero siempre discreta y distribuida en filas.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_03.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Circular',
        texto:
          'Se utiliza para representar la proporción de elementos de cada uno de los valores de la variable.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_04.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Tallos y hojas',
        texto:
          'Es un semigráfico que permite presentar la distribución de una variable cuantitativa. Consiste en separar cada dato en el último dígito (que se denomina <strong>hoja</strong>) y las cifras delanteras restantes (que forman el <strong>tallo</strong>).',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_05.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Diagrama de caja',
        texto:
          'Un diagrama de cajas y bigotes es una manera conveniente de mostrar visualmente grupos de datos numéricos a través de sus cuartiles.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_06.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Diagrama de dispersión',
        texto:
          'Los diagramas de dispersión usan una colección de puntos colocados usando coordenadas cartesianas para mostrar valores de dos variables.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_07.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo: 'Pictograma',
        texto:
          'Los pictogramas son tipos de tablas y gráficos que utilizan íconos e imágenes para representar datos.',
        imagen: require('@/assets/curso/temas/slider_imagenes/slide_A_08.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
    ],
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

<style lang="sass"></style>

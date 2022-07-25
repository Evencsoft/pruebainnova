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
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/template/img-placeholder.svg'),
        // leyendaImagen: 'Leyenda de la imagen',
      },
      {
        titulo:
          'Never, never assume that what you have achieved is good enough',
        texto:
          'Your rapidograph pens are dried up, the x-acto blades in your bag are rusty, and your mind is dull. Stop clicking your mouse, get messy, go back to the basics and make something original.',
        imagen: require('@/assets/template/img-placeholder.svg'),
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

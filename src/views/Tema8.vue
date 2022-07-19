<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 8
      h1 Carrusel de tarjetas

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/carrusel/carrusel.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 El carrusel de tarjetas es un componente web que permite mostrar un grupo de tarjetas de manera secuencial. Las tarjetas están compuestas de iconos y/o imágenes acompañadas de texto.

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Carrusel de tarjetas
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de un carrusel de tarjetas. 
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
              li 
                i.fas.fa-angle-right.txt--orange
                | Se deben utilizar máximo 8 tarjetas por carrusel.

          
    

    separador

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados


    .row.justify-content-center
      .col-lg-4
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/temas/carrusel/carrusel_01.png", alt="alt").img400.m-auto
      .col-lg-8
        p Desde el punto de vista del trabajo archivístico, las tablas de retención documental son fundamentales, porque:

        SlyderF.custom.mb-5(columnas="col-lg-6 col-xl-4")
          .tarjeta.tarjeta--slyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/carrusel/carrusel_02.svg", alt="alt").img100.m-auto     
            p.text-center.mb-0 Permiten el manejo integral de los documentos.

          .tarjeta.tarjeta--slyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/carrusel/carrusel_03.svg", alt="alt").img100.m-auto        
            p.text-center.mb-0 Facilitan la organización de los documentos a partir del concepto de archivo total.

          .tarjeta.tarjeta--slyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/carrusel/carrusel_04.svg", alt="alt").img100.m-auto       
            p.text-center.mb-0 Ayudan a controlar la producción y trámite documental.

          .tarjeta.tarjeta--slyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/carrusel/carrusel_05.svg", alt="alt").img100.m-auto       
            p.text-center.mb-0 Identifican y reflejan las funciones institucionales.

          .tarjeta.tarjeta--slyder.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src="@/assets/curso/temas/carrusel/carrusel_06.svg", alt="alt").img100.m-auto       
            p.text-center.mb-0 Integran los procesos archivísticos para el manejo racional de los documentos. 

    

</template>

<script>
export default {
  name: 'Tema8',
  data: () => ({
    // variables de vue
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

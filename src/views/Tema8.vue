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

    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] vista individual

    .row.justify-content-center.mb-5
      .col-md-6
        SlyderF(columnas="col-12")
          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
            h2.text-center John Doe
            p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
            h2.text-center John Doe
            p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

          .tarjeta.color-acento-botones.p-4
            .row.justify-content-center.mb-3
              .col-8
                img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
            h2.text-center John Doe
            p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

    hr.my-4

    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Vista grupal

    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center FIRST
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 2
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 3
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 4
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 5
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 6
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center 7
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.

      .tarjeta.color-acento-botones.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/componentes/ej-05.svg' alt='AvatarTop')
        h2.text-center LAST
        p.text-center moment. Abandon the shelter of insecurity. Be bold. Greatness isn’t the height of your stature, it’s the heft of your spirit.



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

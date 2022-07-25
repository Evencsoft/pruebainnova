<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Slider de diapositivas

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/sliders/Diapositivas.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 El Slider de diapositivas es un componente web que permite representar de manera secuencial múltiples escenas o diapositivas, las cuales están compuestas de imágenes y texto. En algunos casos se puede hacer uso de componentes interactivos sencillos dentro de cada una de las diapositivas. 

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
                | No utilizar grandes extensiones de texto, los slider generalmente se utilizan para representar ideas o sucesiones de subtemas de manera sintética.
              li 
                i.fas.fa-angle-right.txt--orange
                | Las imágenes y textos sugeridos deben ser lo suficientemente ilustrativos con el fin de trasmitir claramente el contenido.
              li 
                i.fas.fa-angle-right.txt--orange
                | El texto debe estar de forma editable no en imagen, de manera que se pueda copiar y pegar.  
              li 
                i.fas.fa-angle-right.txt--orange
                | La información debe estar bien organizada y esquematizada.

    separador

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados

    #t_6_1
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2]6.1 Slider simple
    .tarjeta.tarjeta--azul.p-4.mb-5    
      SlyderA
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen  

          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    hr.my-4
    .tarjeta.tarjeta--azul.p-4.mb-5
      SlyderA(tipo="b")
        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen  

          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    #t_6_2
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2] 6.2 Slider con Titulo

    .tarjeta.tarjeta--gris.p-4.mb-5
      PasosB.color-acento-contenido
        .row(titulo="Titulo 1")
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

        .row(titulo="Titulo 2")
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen          
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    hr.my-4
    .tarjeta.tarjeta--gris.p-4.mb-5
      LineaTiempoC.color-acento-contenido(text-small)
        .row(titulo="Titulo 3")
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen


        .row(titulo="Titulo 4")
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen   

          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    #t_6_3
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2] 6.2 Numeral o pasos

    .tarjeta.tarjeta--gris.p-4.mb-5
      PasosB.color-acento-contenido
        .row(titulo="")
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
        
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

        .row(titulo="")
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen          
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.    


    

</template>

<script>
export default {
  name: 'Tema6',
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

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

        p.mb-4 Son interactivas con el usuario dado que se requiere que éste deslice la información manualmente permitiendo así que pueda tomarse su tiempo para leer, comprender y regresar a una información anterior en el momento que lo crea conveniente.

        p.mb-4 Su uso está determinado por la extensión del tema o cuando hay:
          ul
            li - Tópicos y subtópicos
            li - Secuencia, sucesos o casos
            li - Secciones
            li - Procedimientos
            li - Narraciones o historias


    separador

    #t_6_1.titulo-segundo.color-acento-contenido
      h2 6.1 Slide navegación simple

    p.mb-4 Provee mayor espacio para la explicación textual así que es óptima para la definición de conceptos completos y extensos. No se asocia a pasos específicos o tipificaciones sino que puede abarcar una temática completa dividida en secciones.

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

    .row
      .col-lg-12.order-2.order-lg-1
        TabsA.color-acento-botones
          .tarjeta.clr--gris.p-4(titulo="Requerimientos de información")
            ul.lista-ul.mb-0
              li
                i.fas.fa-angle-right.txt--orange
                | Título o subtítulo de la temática que se aborda
              li
                i.fas.fa-angle-right.txt--orange
                | Colocar una breve descripción del tema que se aborda en el slide
              li
                i.fas.fa-angle-right.txt--orange
                | Colocar el texto que va en cada diapositiva según el formato instruccional


            p.mb-4 A continuación se presenta el formato instruccional el cual cuenta con las especificaciones necesarias para la producción del slide de diapositivas

            .tarjeta.color-primario.p-3
              .row.justify-content-around.align-items-center
                .col-auto
                  img(src="@/assets/template/document.svg").img65
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h4.mb-1 Formato instruccional - Slide diapositivas (Simple)
                      p.mb-0.text-small Formato de Diseño Instruccional para la creación de infografías interactivas.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://docs.google.com/document/d/1rW0rAr-l4yHGMhfiDchdQOh66LqaMxK9wKRWxwVIvv8/edit?usp=sharing" target="_blank")
                        span Descargar
                        i.fas.fa-file-download

          .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
            .slyderB_bg_01.px-5.py-3.mb-5
              SlyderA(tipo="b")
                .row.justify-content-center.align-items-center.my-lg-4
                  .col-lg-8.mb-4.mb-lg-0.pt-5.pt-0.position-relative
                    .number(data-number="01")
                      h4.ps-4 <i>Determine cuáles LEADS están listos para hacerles seguimiento:</i>
                      p.ps-4.mb-0 Debe hacer un análisis de los datos que obtenga de los LEADS, sobre el interés que han mostrado por los productos y servicios ofertados, cuál es el tipo de empresa y que necesidades presenta. Con estos datos puede determinar el cliente puede convertirse en un cliente fiel y determinar el trato que debe tener, es decir realizar una clasificación del cliente exponencial a futuro y con esto, deberá disponer de la persona de ventas adecuada que logre efectivamente cerrar la venta con LEAD. Esta clasificación de LEADS, le permite, contactar en el momento adecuado, escoger su personal acertado, convencer a su nuevo cliente más fácilmente y conseguir clientes fieles de manera óptima.
                  .col-6.col-lg-4
                    figure
                      img(src='@/assets/curso/temas/sliders/sliderB_01.svg')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-lg-8.mb-4.mb-lg-0.pt-5.pt-0.position-relative
                    .number(data-number="02")
                      h4.ps-4 <i>El tiempo lo es todo, ¿cuándo se debe hacer un seguimiento?</i>
                      p.ps-4.mb-0 El mejor momento para realizar un primer contacto con un LEAD, es inmediatamente cuando el LEAD muestra interés en los productos y servicios. Los LEADS que estén interesados en los productos y que van a comprar, les atraerá, la atención inmediata que le suministre el personal de ventas y si no lo hace una empresa, la competencia estará lista para quedarse con los LEADS. Cuando un equipo de ventas, atiende a los LEADS, podrá aprovechar para obtener de ellos datos específicos de sus intereses vs productos.
                  .col-6.col-lg-4
                    figure
                      img(src='@/assets/curso/temas/sliders/sliderB_02.svg')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-lg-8.mb-4.mb-lg-0.pt-5.pt-0.position-relative
                    .number(data-number="03")
                      h4.ps-4 <i>Conocer dónde están, ¿cómo hacer un seguimiento?</i>
                      p.ps-4.mb-0 Inicialmente, determine qué tipo de comunicación prefieren los LEADS, ya sea presencialmente, por teléfono, por chats, por correo o mensajes de texto y es la primera buena impresión que van a tener de la empresa y que no se van a incomodar. Seguido a esto, el contenido de la primera entrevista con un LEAD, debe ser muy atrayente e impactante, que el contenido haga que el LEAD se interese más por los productos y llegue a un cierre exitoso de venta.
                  .col-6.col-lg-4
                    figure
                      img(src='@/assets/curso/temas/sliders/sliderB_03.svg')

                .row.justify-content-center.align-items-center.my-lg-4
                  .col-lg-8.mb-4.mb-lg-0.pt-5.pt-0.position-relative
                    .number(data-number="04")
                      p.ps-4.mb-0 Con las herramientas que proporciona la tecnología, el equipo de ventas, debe estar muy de la mano con el equipo de marketing para lograr una consecución efectiva y grande de LEADS, mediante las redes sociales y la publicidad en general.
                  .col-6.col-lg-4
                    figure
                      img(src='@/assets/curso/temas/sliders/sliderB_04.svg')


    separador

    #t_6_2.titulo-segundo.color-acento-contenido
      h2 6.2 Slide navegación con numerales.

    p.mb-4 Ideal para textos cortos, bien sea para un procedimiento, una historia, definiciones pequeñas o características puntuales. También podría usarse para plantear ejemplos cuando una situación o temática tiene diferentes variables.

    p.mb-4 La composición gráfica puede tomar el protagónico siendo muy explicativa. Los pasos irán numerados, no nombrados.

    p.mb-4 Se recomienda usar máximo 10 pasos y mínimo 4.

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


    .row
      .col-lg-12.order-2.order-lg-1
        TabsA.color-acento-botones
          .tarjeta.clr--gris.p-4(titulo="Requerimientos de información")
            ul.lista-ul.mb-0
              li
                i.fas.fa-angle-right.txt--orange
                | Título o subtítulo de la temática que se aborda
              li
                i.fas.fa-angle-right.txt--orange
                | Colocar una breve descripción del tema que se aborda en el slide
              li
                i.fas.fa-angle-right.txt--orange
                | Colocar el texto que va en cada diapositiva según el formato instruccional


            p.mb-4 A continuación se presenta el formato instruccional el cual cuenta con las especificaciones necesarias para la producción del slide de diapositivas

            .tarjeta.color-primario.p-3
              .row.justify-content-around.align-items-center
                .col-auto
                  img(src="@/assets/template/document.svg").img65
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h4.mb-1 Formato instruccional - Slide diapositivas (Títulos)
                      p.mb-0.text-small Formato de Diseño Instruccional para la creación de infografías interactivas.
                    .col-sm-auto
                      a.boton.color-acento-botones(href="https://docs.google.com/document/d/1g6fMSTR-6mclIg_S-JgSTZyWKD894kKfSDSaNY63G7c/edit?usp=sharing" target="_blank")
                        span Descargar
                        i.fas.fa-file-download

          .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")

            .p-4.mb-5.pb-0(style='background-color: #F2E6DD; border-top-left-radius: 20px; border-top-right-radius: 20px;')
              PasosB.color-acento-botones
                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_01.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_02.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_03.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_04.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_05.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_06.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_07.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_08.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_09.svg', alt='Texto que describa la imagen')

                .row(titulo="")
                  .col-md-12.mb-4.mb-md-0
                    figure
                      img(src='@/assets/curso/temas/sliders/pasos_10.svg', alt='Texto que describa la imagen')


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

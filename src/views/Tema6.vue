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

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - slider de diapositivas
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de sliders de diapositivas. 
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

          .tarjeta.clr--gris.p-4(titulo="Recomendaciones del diseñador")

    

    separador

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados

    #t_6_1
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2]6.1 Slider - Pasos

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

    #t_6_2
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2] 6.2 Hitos

    .tarjeta.bg3.p-4.mb-5
      LineaTiempoC.color-secundario(text-small)
        .row.align-items-center(titulo="Prehistoria").p-4
          .col-lg-5
            figure
              img(src='@/assets/curso/temas/sliders/LT_01.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-7
            h4 La tecnología en la prehistoria
            p Inicialmente el ser humano desarrolló avances tecnológicos como respuesta a la supervivencia y para eso elaboró instrumentos para cazar, protegerse de los animales, etc.

        .row.align-items-center(titulo="Edad Antigua").p-4
          .col-lg-5
            figure
              img(src='@/assets/curso/temas/sliders/LT_02.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-7
            h4 La tecnología en la Edad Antigua
            p En esta etapa de la historia se generó la escritura, sin embargo, las primeras plumas comenzaron a usarse en el año 3000 a.C. por la antigua civilización egipcia para la elaboración de papiros y otros manuscritos.
            p Por otra parte, es realmente asombroso que culturas antiguas como la egipcia y otras que surgieron miles de años antes de Cristo, tengan evidencia de enormes avances en ingeniería para la época y con construcciones de mucho nivel como los que se reflejan en las pirámides de Egipto.

        .row.align-items-center(titulo="Edad Media").p-4
          .col-lg-5
            figure
              img(src='@/assets/curso/temas/sliders/LT_03.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-7
            h4 La tecnología en la Edad Media
            p El ser humano empezó a emplear máquinas simples, como molinos de viento, y máquinas a vapor que permitan sustituir la tracción animal y generaban más eficiencia y permitían el comercio entre lugares lejanos. Algunos inventos correspondientes a esta época son: los relojes, molinos de viento, la brújula, entre otros.
            p En esta edad es representativo la invención de la imprenta, con la  cual mejoró notablemente la comunicación entre las diferentes poblaciones.

        .row.align-items-center(titulo="Edad Moderna").p-4
          .col-lg-5
            figure
              img(src='@/assets/curso/temas/sliders/LT_04.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-7
            h4 La tecnología en la Edad Moderna
            p Esta época se caracteriza por la invención de artefactos como el telescopio, microscopio, reloj de péndulo, lápiz, calculadora, entre otros.
            h5 Revoluciones industriales
            p El conocimiento de la física y la ciencia en general permitió que los avances siguieran siendo representativos a tal punto que se han vivido cuatro revoluciones industriales que influyeron no solo en la productividad, sino en el tipo de empleos y de emprendimientos que surgieron.

        .row.align-items-center(titulo="Edad Contemporánea").p-4
          .col-lg-5
            figure
              img(src='@/assets/curso/temas/sliders/LT_05.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-7
            h4 La tecnología en la Edad Contemporánea
            h5 Transición de lo análogo a lo digital
            p Ahora pensemos por un momento en lo que sucedía en los años 90: si una persona quería entregar un trabajo escrito, debía hacerlo a mano o utilizar una máquina de escribir, esta última generó un impacto positivo para quien tenía dificultades al leer diversas caligrafías; pero si en la actualidad un joven utiliza esta máquina de seguro encontrará dificultades impensables hoy, por ejemplo si cometemos un error al escribir un texto hoy, simplemente lo borramos o presionamos “deshacer” en un software, pero con una máquina de escribir simplemente se arrancaba la hoja y había que empezar de nuevo.

        .row.align-items-center(titulo="Edad digital").p-4
          .col-lg-4
            figure
              img(src='@/assets/curso/temas/sliders/LT_06.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-8
            h4 La tecnología en la Edad Contemporánea
            h5 Tecnología móvil
            p Cuando los microchips empezaron a ser más conocidos y usados, la electrónica se extendió de manera más rápida y surgieron computadores, localizadores, elementos digitales y poco a poco fueron avanzando hasta llegar a tener diversos tamaños como por ejemplo en teléfonos donde se integran tecnologías de audio y video, con procesadores de textos, sistemas operativos que permiten realizar procesos para los cuales antes se necesitaban varios dispositivos. 
            p Hoy un teléfono nos permite escanear un documento y enviarlo por correo en poco tiempo pero, además, permite que emprendedores de esta era puedan realizar un diseño de un banner con una simple aplicación móvil, subirlo a una red social o enviarlo por diversos sistemas de mensajería a muchos clientes. 
            p Estamos en una era digital donde la información y la tecnología están al alcance de todos y es importante reflexionar sobre los aprendizajes que se vienen en los próximos años.

        .row.align-items-center(titulo="Emprendimiento digital").p-4
          .col-lg-4
            figure
              img(src='@/assets/curso/temas/sliders/LT_07.png' alt='Hombres primitivos con un mamut').mb-4
          .col-lg-8
            h4 La tecnología y el emprendimiento digital
            p Los emprendimientos no son ajenos a la realidad de esta era digital, ya que muchos han ampliado sus canales de ventas y ya no solo tienen un espacio físico, sino también uno virtual y, en muchos casos, gratuitos como en redes sociales donde se pueden cerrar negocios por medio de pantallas y transacciones digitales. 
            p Las barreras de las distancias empiezan a desvanecerse y aparecen nuevas necesidades de aprendizaje y adaptación a estilos, negociaciones, habilidades blandas y digitales, entre otras. 
            p La era digital va a dar mucho de qué hablar y un emprendedor que analiza su entorno sabe que debe prepararse para todos estos cambios y apropiarse de estas nuevas habilidades.
    
    #t_6_3
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2] Presentación

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

    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange.pe-2] Citas

    .tarjeta.bg2.mb-5.boxShadow
      SlyderA.p-5
        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/sliders/slider_Q1.png' alt='')
          .col-md-8
            .bloque-texto-f.color-primario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto.text-center Es una sociedad humana asentada de manera permanente en el territorio que le corresponde, sujeta a un poder soberano que crea, define y aplica un orden jurídico que estructura la sociedad estatal para obtener el bien público temporal de sus componentes.
              .bloque-texto-f__autor.mb-3
                h3.mb-0.text-center Platón (s.f)

        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/sliders/slider_Q2.png' alt='')
          .col-md-8
            .bloque-texto-f.color-primario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto.text-center Es una agrupación humana fijada en un territorio determinado y en la que existe un orden social, político y jurídico orientado hacia un bien común, establecido y mantenido por una autoridad dotada de poder de coerción.
              .bloque-texto-f__autor.mb-3
                h3.mb-0.text-center André Hauriou- Jurista Francés (s.f)

        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/sliders/slider_Q3.png' alt='')
          .col-md-8
            .bloque-texto-f.color-primario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto.text-center La asociación perfecta de hombres libres unidos para gozar de sus derechos y para la utilidad común. Es la asociación política soberana que dispone de un territorio propio, con una organización específica y un supremo poder facultado para crear el derecho positivo.
              .bloque-texto-f__autor.mb-3
                h3.mb-0.text-center H. Grocio (s.f)

        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/sliders/slider_Q4.png' alt='')
          .col-md-8
            .bloque-texto-f.color-primario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto.text-center El Estado “Una comunidad organizada en territorio definido, mediante un orden jurídico servido por un cuerpo de funcionarios y definido y organizado por un poder jurídico, autónomo y centralizado que tiende a realizar el bien común, en el ámbito de esa comunidad”
              .bloque-texto-f__autor.mb-3
                h3.mb-0.text-center Sánchez Agesta. (s.f)

        .row.justify-content-center.align-items-center
          .col-md-3.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/temas/sliders/slider_Q5.png' alt='')
          .col-md-8
            .bloque-texto-f.color-primario.pt-4.px-5
              .bloque-texto-f__comillas
                i.fas.fa-quote-left
                i.fas.fa-quote-right
              h4.text-regular.bloque-texto-f__texto.text-center Colombia es un Estado social de derecho, organizado en forma de República unitaria, descentralizada, con autonomía de sus entidades territoriales, democrática, participativa y pluralista, fundada en el respeto de la dignidad humana, en el trabajo y la solidaridad de las personas que la integran y en la prevalencia del interés general”.
              .bloque-texto-f__autor.mb-3
                h3.mb-0.text-center Constitución Política de Colombia (1991)

    

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

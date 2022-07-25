<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Actividades didácticas

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/actividad/actividad_didactica.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4
          p.mb-0 Una actividad didáctica es el conjunto de componentes interactivos propuestas a los alumnos para alcanzar los objetivos determinados de aprendizaje. Una componente formativo puede incluir una o varias de estas actividades.

    .row
      .col-lg-12.order-2.order-lg-1
        TabsA.color-acento-botones      
          .tarjeta.clr--gris.p-4(titulo="Requerimientos de información")
            ul.lista-ul.mb-0
              li 
                i.fas.fa-angle-right.txt--orange
                | Titulo de la actividad didáctica corto, ilustrativo y llamativo.
              li 
                i.fas.fa-angle-right.txt--orange
                | Objetivo de la actividad didáctica

          
          
    separador    

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados

    #t_5_1
    Dialogo.color-primario(:dialogo="dialogo").mb-2
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Greeting the doctor. / Saludando al doctor.
      template(#descripcion-actividad) Escuche los audios y complete los espacios en blanco de cada una de las frases arrastrando el término correcto.   

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Falso y verdadero
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra
    

    #t_5_2
    .tarjeta.clr--gris.p-5.mb-2
      .row.justify-content-around.align-items-center
        .col-8.col-lg-5.mb-4.mb-md-0
          img(src="@/assets/curso/temas/actividad/actividad_05.png").mb-3   

        .col-md.col-lg-6
          h3 Cuestionario
          p.mb-4 #[strong Falso o verdadero.] Lea la afirmación de cada ítem y seleccione la respuesta falso o verdadero según corresponda.          
          a.boton.boton--b(:href="obtenerLink('/actividades/AD5/story.html')" target="_blank")
            span Realizar
            i.fas.fa-puzzle-piece     

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Falso y verdadero
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra     
    

    .tarjeta.clr--gris.p-5.mb-2
      .row.justify-content-around.align-items-center
        .col-8.col-lg-5.mb-4.mb-md-0
          img(src="@/assets/curso/temas/actividad/actividad_02.png").mb-3

          a.anexo.cstm(:href="obtenerLink('/downloads/formatos/formato_5_actividad_didactica_opcion_multiple.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/template/icono-doc.svg")
            .anexo__texto
              p Formato instruccional - muestra

        .col-md.col-lg-6
          h3 Cuestionario
          p.mb-4 #[strong Opción múltiple.] Lea la afirmación de cada ítem y luego señale la respuesta correcta según corresponda.
          
          a.boton.boton--b(:href="obtenerLink('/actividades/AD2/story.html')" target="_blank")
            span Realizar
            i.fas.fa-puzzle-piece   

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Opción múltiple
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra 

    
    

    #t_5_3
    .tarjeta.clr--gris.p-5.mb-2
      .row.justify-content-around.align-items-center
        .col-8.col-lg-5.mb-4.mb-md-0
          img(src="@/assets/curso/temas/actividad/actividad_01.png").mb-3         

        .col-md.col-lg-6
          h3 Relación de términos
          p.mb-4 #[strong Arrastrar y soltar coincidencias.] De acuerdo a la definición planteada en la columna izquierda, arrastre cada término al lugar que considere correcto de la columna derecha. 
          a.boton.boton--b(:href="obtenerLink('/actividades/AD1/story.html')" target="_blank")
            span Realizar
            i.fas.fa-puzzle-piece      
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Relación de términos
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra 

    #t_5_4
    .tarjeta.clr--gris.p-5.mb-2
      .row.justify-content-around.align-items-center
        .col-8.col-lg-5.mb-4.mb-md-0
          img(src="@/assets/curso/temas/actividad/actividad_03.png").mb-3         

        .col-md.col-lg-6
          h3 Completar frases
          p.mb-4 #[strong Completar frases.] Escuche los audios, complete los espacios en blanco de cada una de las frases y luego haga clic en el botón "Verificar respuesta"
          
          a.boton.boton--b(:href="obtenerLink('/actividades/AD3/story.html')" target="_blank")
            span Realizar
            i.fas.fa-puzzle-piece      
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Completar frases
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra  

    
    .tarjeta.clr--gris.p-5.mb-2
      .row.justify-content-around.align-items-center
        .col-8.col-lg-5.mb-4.mb-md-0
          img(src="@/assets/curso/temas/actividad/actividad_04.png").mb-3          

        .col-md.col-lg-6
          h3 Completar frases
          p.mb-4 #[strong Completar frases.] Complete los espacios en blanco de cada una de las frases y luego haga clic en el botón "Verificar respuesta".
          
          a.boton.boton--b(:href="obtenerLink('/actividades/AD4/story.html')" target="_blank")
            span Realizar
            i.fas.fa-puzzle-piece      
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Opción múltiple
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de actividades didácticas tipo cuestionario. 
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
      .col-lg-4
        a.anexo(:href="obtenerLink('/downloads/formato_5_actividad_didactica_falso_verdadero.docx')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-doc.svg")
          .anexo__texto
            p Formato instruccional - muestra 

    

    
    

</template>

<script>
export default {
  name: 'Tema5',
  data() {
    return {
      dialogo: {
        personajes: [
          {
            nombre: 'Doctor',
            img: require('@/assets/curso/temas/doctor.svg'),
          },
          {
            nombre: 'Jonathan',
            img: require('@/assets/curso/temas/jonathan.svg'),
          },
        ],
        dialogo: [
          {
            personaje: 'Jonathan',
            textoIng: 'Hello, Doctor. How are ***?',
            textoEsp: 'Hola, doctor. ¿Cómo estás?',
            audio: require('@/assets/audio/1.mp3'),
            palabra: 'you',
          },
          {
            personaje: 'Doctor',
            textoIng: 'Good *** Jonathan.',
            textoEsp: 'Buenos días Jonathan .',
            audio: require('@/assets/audio/2.wav'),
            palabra: 'morning',
          },
          {
            personaje: 'Doctor',
            textoIng: 'I am ***. How are you doing?.',
            textoEsp: 'Estoy bien, ¿cómo estás?',
            audio: require('@/assets/audio/3.wav'),
            palabra: 'great',
          },
          {
            personaje: 'Jonathan',
            textoIng: 'I&#8217m doing very well. I&#8217m feeling better.',
            textoEsp: 'Estoy muy bien. Me siento mejor.',
            audio: require('@/assets/audio/4.mp3'),
          },
          {
            personaje: 'Doctor',
            textoIng: 'It was *** to see you! I am glad you feel better.',
            textoEsp: ' ¡Qué gusto verte! Me alegro de que te sientas mejor.',
            audio: require('@/assets/audio/5.wav'),
            palabra: 'nice',
          },
          {
            personaje: 'Jonathan',
            textoIng: ' Thank you Doctor. *** a great day! ',
            textoEsp: 'Gracias Doctor. ¡Qué tengas un lindo día! ',
            audio: require('@/assets/audio/6.mp3'),
            palabra: 'have',
          },
          {
            personaje: 'Doctor',
            textoIng: ' ***.',
            textoEsp: 'Adiós.',
            audio: require('@/assets/audio/7.wav'),
            palabra: ' Goodbye. ',
          },
        ],
      },
    }
  },
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

<style lang="sass">
.tarjeta-reproductor
  &--izquierda
    position: relative
    &__img
      width: 300px
      position: absolute
      height: 100%
      left: 0
      bottom: 0
      transform: translateX(-30%) translateY(0%)
  &--derecha
    position: relative
    &__img
      width: 300px
      margin: 0 auto
      position: absolute
      height: 100%
      right: 0
      bottom: 0
      transform: translateX(30%) translateY(10%)
.franja
  position: relative
  &:before
    content: ''
    position: absolute
    bottom: 0%
    left: 0
    width: 100%
    height: 35%
    background-color: #ffd947
    z-index: 0
  .content
    position: inherit
.slyder__btn
  background-color: $color-acento-contenido
  i
    color: white !important
</style>

<style lang="sass"></style>

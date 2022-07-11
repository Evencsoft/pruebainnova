<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4 
      h1 Videos

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/video/video.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Video
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de videos. 
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
                | Contenido máx 25 palabras por escena y dejar palabras destacadas en negrilla.
              li 
                i.fas.fa-angle-right.txt--orange
                | La información debe ser explicada de forma clara y sencilla, que se pueda dar a nivel visual, para esto se requiere imágenes o analogías que aclaren aun concepto cercano. 
              li 
                i.fas.fa-angle-right.txt--orange
                | El texto debe estar de forma editable no en imagen, de manera que se pueda copiar y pegar.
              li 
                i.fas.fa-angle-right.txt--orange
                | Si el guion trae tablas no deben ser complejas ni muy largas, dada la naturaleza del recurso. 
              li 
                i.fas.fa-angle-right.txt--orange
                | El guion debe tener una extensión de máximo 500 palabras que equivalen a 3 minutos, ya que 1 minuto equivale a 166 palabras.   

          .tarjeta.clr--gris.p-4(titulo="Recomendaciones del diseñador ")      

    separador     

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados

    #t_4_1
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Video - Spot animado

    TabsA.color-acento-botones.mb-5    
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/-rq4_7xgFLM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/cCxnzKy-hLU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 3")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/8gZTBdLt_IM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)            

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 4")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/B9m7htWTfLM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)         

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 5")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/OjFiFv0OTQk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)            

    #t_4_2
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Video - animación 2D

    TabsA.color-acento-botones.mb-5    
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/RtpjVC6FGxE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)   

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/3KDDv2LrIcE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)   

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 3")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/QCcIP7JTo-0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 4")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/p46ll0IMsHM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 5")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/BP8OeszBSCc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

    #t_4_3
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Video - motion

    TabsA.color-acento-botones.mb-5    
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/vdPrCjWJSHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)               

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/1TvhnYvYgfw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)      

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 3")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/Z9zSnDD46IU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)       

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 4")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/-G8D2UP9ZiY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)              

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 5")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/GXTHrucLiac" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

    #t_4_4
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Video - clase /  tutorial

    TabsA.color-acento-botones.mb-5    
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/FgZTUUgIcIE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)             

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/QX6KE8AAjPQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 3")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/ukQDLsmigv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)  

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 4")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/ypl9CSSDRZ8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)             

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 5")
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/HTaVk0eKNO0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    #t_4_5
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Video - oferta del programa

    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/jASywqOHrQM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)        

</template>

<script>
export default {
  name: 'Tema4',
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

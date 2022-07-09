<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Infografía estática

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/infografia/infografia.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 Las infografías son datos presentados con el auxilio de recursos visuales. #[strong Siempre que usamos imágenes para explicar datos, tenemos un infografía]. 

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Infografía estática
                  p.mb-0.text-small Formato de Diseño Instruccional para la creación de infografías estáticas.
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
                | Título corto
              
          .tarjeta.clr--gris.p-4(titulo="Recomendaciones del diseñador")
            p #[strong 1) Definir un tema.]
              ul.lista-ul.ps-4
                li 
                  i.fas.fa-angle-right.txt--orange
                  | Explicación de un concepto.
                li 
                  i.fas.fa-angle-right.txt--orange
                  | Explicación de una tecnología o proceso.
                li 
                  i.fas.fa-angle-right.txt--orange
                  | Representación de datos estadísticos, biográficos, geográficos, etc.
                li 
                  i.fas.fa-angle-right.txt--orange
                  | Resumen de un documento.

              .hr--line
              p.mb-0 #[strong 2) Elegir un título atractivo.]<br> Se debe captar la atención del lector por medio de títulos cortos y llamativos que representen correctamente el contenido abordado. 
              .hr--line
              p.mb-0 #[strong 3) Utilizar oraciones cortas y objetivas.]
              .hr--line
              p.mb-0 #[strong 4) Utilizar términos simples y fáciles de entender.]
              .hr--line
              p.mb-0 #[strong 5) La información debe estar bien organizada y esquematizada.]
              .hr--line
              p.mb-0 #[strong 6) Se debe hacer mayor énfasis en el lenguaje esquemático y pictórico.]
              .hr--line
              p.mb-0 #[strong 7) Los gráficos, diagramas, iconos y demás elementos planteados deben ser claros y específicos.]

    separador        

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados 

    .tarjeta.color-acento-botones.p-4.p-md-5.mb-5
      .row.justify-content-around.align-items-center
        .col-8.col-sm-5.col-md-4.mb-4.mb-md-0
          img(src="@/assets/componentes/ej-01.png")

        .col-md.col-lg-6
          h3 Psicología de la moda: sexualidad, ropa mágica, ropa malévola y ropa neurótica.
          p.mb-4 La conexión entre el vestuario y la persona que lo porta es lo que llamamos proceso efectivo de comunicación de las marcas, direccionado desde la psicología de la moda, lo invitamos a profundizar en esta temática consultando el siguiente recurso infografico.
          
          a.boton.color-acento-contenido.texto-blanco(:href="obtenerLink('/downloads/Infografia_Psicologia_de_moda.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download   

    
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

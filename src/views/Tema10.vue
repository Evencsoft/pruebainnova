<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 10
      h1 Pestañas o tabs

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/pestañas/pestañas.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 La navegación por pestañas se refiere a la posibilidad de que varios paneles con información estén contenidos dentro de una sola ventana principal, usando pestañas para alternar entre ellos.

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Pestañas o tabs
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de pestañas o tabs. 
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

          .tarjeta.clr--gris.p-4(titulo="Recomendaciones del diseñador")

    separador    

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados   

    h3.mb-5 #[i.fas.fa-angle-double-right.txt--orange] Pestañas verticales    

    .row
      .col-lg-8.order-2.order-lg-1
        TabsA.color-acento-botones.mb-5        
          .tarjeta.clr-paleYellow.p-4(titulo="Leyes")
            h4 Leyes
            p Ley 100 de 1993 - Por la cual se crea el Sistema de Seguridad Social Integral y se dictan otras disposiciones.
              br
              br
              | Ley 1562 de 2012 - Por la cual se modifica el Sistema de Riesgos Laborales y se dictan otras disposiciones en materia de salud ocupacional.

          .tarjeta.clr-paleYellow.p-4(titulo="Decretos")
            h4 Decretos
            p Decreto 1295 de 1994 - Determina la organización y administración del Sistema General de Riesgos Profesionales. 
              br
              br
              | Decreto 1072 de 2015 - Decreto Único Reglamentario del Sector Trabajo.
              br
              br
              | Decreto 780 de 2016 - Por medio del cual se expide el Decreto Único Reglamentario del Sector Salud y Protección Social.
              br
              br
              | Decreto 2058 de 2018 - Por la cual se modifica el Título 2 de la Parte 1 y el artículo 2.1.5.1 del Decreto 780 de 2016, Único Reglamentario del Sector Salud y Protección Social.

          .tarjeta.clr-paleYellow.p-4(titulo="Resoluciones")
            h4 Resoluciones
            p Resolución 3310 de 2018 - Por la cual se adopta el Formulario Único de Afiliación y Reporte de Novedades al Sistema General de Riesgos Laborales y dictan otras disposiciones.
              br
              br
              | Resolución 2389 de 2019 - Por la cual se definen los lineamientos generales para la operación del Sistema General de Riesgos Laborales-SGRL en el Sistema de Afiliación Transaccional – SAT y se adopta el formulario de afiliación y traslado del empleador al Sistema General de Riesgos Laborales.
              br
              br
              | Resolución 2945 de 2019 - Por la cual se modifica la Resolución 2389 de 2019 en relación con la ampliación de unos plazos y se dictan otras disposiciones.
      .col-lg-4.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/temas/pestañas/pestañas_verticales.png", alt="alt", style="width:450px;").m-auto

    h3.mb-5 #[i.fas.fa-angle-double-right.txt--orange] Pestañas horizontales - sencillas    

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Archivo de gestión o de oficina")
        .row.justify-content-center
          .col-lg-5.order-2.order-lg-1
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/pestañas/pestañas_01.png', alt='').img400.m-auto
          .col-lg-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura Archivo de gestión o de oficina
            p En este archivo reposan los documentos generados en los procesos de gestión administrativa. El tiempo de permanencia de la documentación en este depende fundamentalmente del trámite y de las normas internas indicadas en las Tablas de Retención Documental - TRD para decidir su traslado al archivo central.

            p Las oficinas deberán transferir al archivo central aquellas series y subseries documentales que hayan cumplido el tiempo de retención señalado, toda transferencia debe ir acompañada de un inventario y debe hacerse de acuerdo con un cronograma previamente acordado entre quienes producen la documentación y la persona encargada del archivo.   

      .py-3.py-md-4(titulo="Archivo central o intermedio")
        .row.justify-content-center          
          .col-lg-7
            h4.txt--purpura Archivo central o intermedio
            p A este archivo son transferidos los documentos de los archivos de gestión cuya consulta no es tan frecuente, es decir, cuando están en su segundo ciclo de vida (semiactivos). El archivo central deberá facilitar la consulta tanto a las oficinas productoras como al público en general de acuerdo a las normas que lo regulen.
            p Recibidos los documentos en el archivo central, el jefe de este deberá constatar que las series y subseries documentales transferidas concuerdan con el inventario que las relaciona, para proceder a incorporarlas en las agrupaciones documentales correspondientes de acuerdo con el cuadro de clasificación establecido para cada oficina.
            p.mb-0 La documentación permanecerá en el archivo central durante el tiempo estipulado en las TRD. Antes de transferir al archivo histórico, se aplicará la disposición final y los procedimientos previstos en la TRD.
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/pestañas/pestañas_02.png', alt='').img400.m-auto      

      .py-3.py-md-4(titulo="Archivo histórico o permanente")
        .row.justify-content-center
          .col-lg-5.order-2.order-lg-1
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/pestañas/pestañas_03.png', alt='').img400.m-auto
          .col-lg-7.order-1.order-lg-2.mb-4.mb-lg-0
            h4.txt--purpura Archivo histórico o permanente
            p Es aquel al cual se transfiere la documentación del archivo central o del archivo de gestión que, por decisión del correspondiente comité de archivos, debe conservarse permanentemente, dado el valor que adquiere para la investigación, la ciencia y la cultura.

            p.mb-0 Los procesos de organización de archivos son tres: clasificación, ordenación y descripción. A pesar de la aparente claridad, la primera dificultad que se encuentra al trabajar en archivos consiste en determinar qué se entiende archivísticamente por cada uno de ellos, pues las palabras mismas requieren atención por parte de los encargados de archivos para aclarar sus especificidades.

    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Pestañas horizontales - iconos

</template>

<script>
export default {
  name: 'Tema10',
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

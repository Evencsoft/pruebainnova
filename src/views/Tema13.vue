<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 13
      h1 Tarjetas
    
    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/tarjetas/tarjetas.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 Las tarjetas se utilizan para agrupar varios contenidos dentro de un contenedor que se puede replicar de manera modular en el contenido del sitio web. 

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Tarjetas
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de tarjetas. 
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

      

    separador

    .titulo-segundo.color-acento-contenido
      h2 Ejemplos destacados

    #t_13_1
    h3.mb-5 #[i.fas.fa-angle-double-right.txt--orange] Tarjetas - avatar

    .bg_img_01
      .row.justify-content-center.mb-5
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-5
              figure
                img(src="@/assets/curso/temas/tarjetas/tar_avatar_ver_01.png", alt="alt").img90.m-auto
            h4.text-center La medición
            p.text-center.mb-0 Los lideres del #[i marketing] se encargan de caracterizar todos los puntos de contacto de un cliente determinado y sus principales datos, conociendo los comportamientos y las prioridades de cada cliente con el fin de enlazar las acciones de #[i marketing] con los resultados comerciales.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-5
              figure
                img(src="@/assets/curso/temas/tarjetas/tar_avatar_ver_02.png", alt="alt").img90.m-auto
            h4.text-center Activación
            p.text-center.mb-0 Se enfoca en la toma asertiva de decisiones por intermedio de instrumentos de automatización con el fin de poder conectarse con los posibles clientes a gran escala, teniendo en cuenta que la estrategia será personalizada, dando respuesta a lo requerido por el cliente.
        .col-lg-4.mb-4.mb-lg-0
          .crd.crd--grayGrad(data-aos="flip-left")
            .bottomCircle.mb-5
              figure
                img(src="@/assets/curso/temas/tarjetas/tar_avatar_ver_03.png", alt="alt").img90.m-auto
            h4.text-center Formas de trabajar
            p.text-center.mb-0 Se centran en estructurar equipos agiles y de respuesta a oportuna, exclusivamente para los clientes, haciendo referencia a las tendencias de #[i marketing], teniendo en cuenta las perspectivas de medición y los canales en los que desarrollan.


    #t_13_2
    h3.mb-5 #[i.fas.fa-angle-double-right.txt--orange] Tarjetas - conectadas

    .row.justify-content-center.mb-5
      .col-lg-9.position-relative
        h3.mb-4.text-center.txt--purpura Elementos determinantes para el análisis - CAC 
        .avatar
          figure
            img(src="@/assets/curso/temas/tarjetas/conectada_01.svg", alt="alt").img250
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tarjetas/conectada_02.svg", alt="alt").img100
            .col
              h5 Calidad de la información
              p Es importante tener en cuenta las variables, la ponderación de estas refleja la calidad de la información, la cual le permitirá obtener información concreta, clara y medible. Es necesario resaltar las características determinantes desde enfoques cualitativos y cuantitativos del dato obtenido. 
        .crd.crd--avatarHorizontal.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tarjetas/conectada_02.svg", alt="alt").img100
            .col
              h5 Aplicación de técnicas
              p Desarrolle técnicas que le permitan tener un panorama completo de la información que se esté analizando, integrando las variables obtenidas en la medición y contrastando detalladamente los datos.
        .crd.crd--avatarHorizontal.crd--last.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/temas/tarjetas/conectada_03.svg", alt="alt").img100
            .col
              h5 Comunicación correcta de los resultados
              p En los análisis de resultados, el determinante es saber mostrar la información, tenga en cuenta la objetividad, la claridad, la transparencia y la organización de la información. 


    #t_13_3 
    h3.mb-5 #[i.fas.fa-angle-double-right.txt--orange] Tarjetas - animadas

    .row.justify-content-center.mb-5
      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tarjetas/tar_hover_01.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Reporte de ventas diarias 
            p.mb-0 Con este tipo de reportes, los gerentes podrán supervisar específicamente, la labor de cada vendedor y de esta manera, saber en qué les va bien y en cuáles actos hay que mejorar. Aquí también, va a encontrar si su fuerza de ventas está entendiendo sus estrategias y le sea más fácil incentivarlos a aumentar su productividad.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tarjetas/tar_hover_02.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Reporte de ventas semanal
            p.mb-0 Con estos reportes semanales, podrá encontrar las dificultades que pueda tener algún o algunos vendedores y evitar que se pierdan los clientes fijos. Reportar semanalmente, le permite tener un equipo de ventas fortalecido y bien direccionado, con las correcciones necesarias para lograr las metas de ventas propuestas.

      .col-xl-4.col-lg-7.col-md-9.col-11.mb-4.mb-xl-0
        .crd_hover_txt(data-aos="flip-left")
          .crd_hover_txt--img
            figure
              img(src="@/assets/curso/temas/tarjetas/tar_hover_03.png", alt="alt")
          .crd_hover_txt--body
            h4.mb-3 Reporte de ventas mensuales
            p.mb-0 Con este tipo de reportes usted va a hacer un seguimiento específico a su equipo de ventas respecto a sus objetivos empresariales a largo plazo.    

</template>

<script>
export default {
  name: 'Tema13',
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

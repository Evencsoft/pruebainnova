<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Acordeones

    .row.justify-content-center.align-items-center
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/acordeones/acordeones.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p.mb-0 Un acordeón está formado por regiones desplegables que permiten mostrar u ocultar contenido pulsando sobre un botón.

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Acordeones
                  p.text-small.mb-0 Formato de Diseño Instruccional para la creación de un acordeón. 
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

    #t_9_1
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Acordeón - tipo 1

    p.mb-4 A continuación, se destacan cuatro ejes principales que tienen que ver con las exigencias de calidad para el cliente, la mejora continua, satisfacción del cliente y la reglamentación en el cumplimiento de la norma, y en el siguiente recurso se detallan cada una de ellas.

    .bg--img_03
      .row.justify-content-center.mb-4
        .col-lg-4
          figure(data-aos="zoom-in")
            img(src="@/assets/curso/temas/acordeones/acord_A_01.png", alt="alt").img400.m-auto
        .col-lg-8
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta acordeonA")
            .row(titulo="ISO 9000, (2005) Sistemas de Gestión de la Calidad. Definiciones y fundamentos")
              .col-12
                p.mb-0 Establece un punto de partida para comprender las normas y define los términos fundamentales utilizados en la familia de normas ISO 9000, que se necesitan para evitar malentendidos en su utilización, especificando el vocabulario clave a utilizar dentro del proceso. 

            .row(titulo="ISO 9001(2015). Sistemas de Gestión de la Calidad. Requisitos")
              .col-12
                p.mb-0 Es la norma que establece los criterios que permiten lograr eficazmente los requisitos del cliente y los reglamentarios, para conseguir la satisfacción del cliente. Incluye los principios de motivación y participación activa de la dirección como el ciclo de mejora continua. Es el único estándar que puede certificarse. Esta norma exige la elaboración de la documentación que debe conservar el sistema de gestión de calidad, sus políticas y procedimientos.

            .row(titulo="ISO 9004. Sistemas de Gestión de la Calidad. Directrices para la mejora del desempeño")
              .col-12
                p.mb-0 Sistemas de Gestión de la Calidad. Directrices para la mejora del desempeño: esta norma proporciona ayuda para la gestión del éxito sostenido del sistema de gestión de la calidad para beneficiar a todas las partes interesadas a través de las mejoras y el mantenimiento de la satisfacción del cliente. La Norma ISO 9004 abarca tanto la eficiencia como la eficacia del sistema de gestión de la calidad.  Se puede tomar como una ampliación de la norma anterior y no es certificable.

            .row(titulo="ISO 19011. Directrices para la auditoría ambiental y de la calidad")
              .col-12
                p.mb-0 Proporciona directrices para verificar la capacidad del sistema para conseguir objetivos de la calidad definidos. Esta norma se puede utilizar internamente para auditar a los proveedores de la organización.

    #t_9_2
    h3.mb-3 #[i.fas.fa-angle-double-right.txt--orange] Acordeón - tipo 2 

    .row.justify-content-center
      .col-lg-8
        p Por lo anterior, se puede hablar de tres fases dentro de todo proceso productivo, las cuales se evidencian en el siguiente recurso de aprendizaje:

        AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta clr--gris")
          .row(titulo="Fase 1: Etapa analítica - Acopio")
            .col-12
              p Es la primera etapa de todo proceso productivo, ya que allí se reúnen las materias primas que serán utilizadas en la fabricación de algún producto.
              p.mb-0 Es acá donde las empresas se centran en conseguir la mayor cantidad de insumos posibles y al menor costo. En esta etapa se debe tener en cuenta los costos de almacenamiento y transporte.   

          .row(titulo="Fase 2: Etapa de síntesis - Producción")
            .col-12
              p En el transcurso de esta etapa es donde las materias primas que se recolectaron previamente pasan por un proceso de transformación, para obtener el producto final que la organización va a comercializar. 
              p Acá es necesario que se definan los diferentes estándares de calidad y sus respectivos controles. 
              p.mb-0 Es de vital importancia que se realice un trabajo exhaustivo de observación y de monitoreo, para que se puedan anticipar cambios y dar cumplimiento a los objetivos pactados. 

          .row(titulo="Fase 3: Etapa de acondicionamiento - Procesamiento")
            .col-12
              p Es la etapa final del proceso donde se adapta el producto a las necesidades del cliente, para la comercialización, el transporte y almacenamiento, al igual que en la etapa analítica juegan un papel crucial, ya que se debe tener un control del producto terminado y unas condiciones adecuadas, para que no se arruine el producto de ninguna manera.
              p.mb-0 Una vez que el producto sea entregado, también es necesario realizar un control que permita establecer si el producto que se entregó cumple con los objetivos y los estándares de calidad que fueron previamente establecidos. 
   
      .col-lg-4.d-none.d-lg-flex
        figure(data-aos="zoom-in")
          img(src="@/assets/curso/temas/acordeones/acord_B_01.png", alt="alt").m-auto
    

</template>

<script>
export default {
  name: 'Tema9',
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

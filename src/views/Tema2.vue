<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Infografía interactiva

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6
        figure
          img(src="@/assets/curso/temas/presentaciones/presentaciones.svg", alt="alt")
      .col-lg-6
        .crd.clr-paleYellow.p-4.mb-4
          p Este tipo de infografía exige un nivel técnico mayor, ya que implica, además de animaciones, conocimiento de programación. 
          p.mb-0 La infografía debe ser manipulable por el usuario, de forma que este consiga interactuar con la información de la pieza por su propia cuenta.  

        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center
            .col-auto
              img(src="@/assets/template/document.svg").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Formato instruccional - Infografía interactiva
                  p.mb-0.text-small Formato de Diseño Instruccional para la creación de infografías interactivas.
                .col-sm-auto
                  a.boton.color-acento-botones(:href="obtenerLink('/downloads/formato_infografia.pdf')" target="_blank")
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

    #t_2_1
    h3.mb-5 2.1 Infografía interactiva - puntos calientes #[i.fas.fa-angle-double-left.txt--orange.ms-2]

    TabsA.color-acento-botones.mb-5        
   
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        .titulo-quinto.color-acento-contenido.mb-3
          h4 Fases de la Crisis
        .imgCont.m-auto
          .row.justify-content-center.mb-4          
            ImagenInfografica.color-acento-botones.mb-5
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/infografia/infografia_01.svg', alt='', style='')
                  
              .tarjeta.color-acento-botones.p-4(x="11%" y="7%" numero="+" style='border-radius: 10px; background-color: #FFE8C8')
                h5.mb-3.text-center Exposición al evento crítico
                p.mb-0.text-center Produce tensión y puede aparecer un estado de shock que protege a la víctima de una condición abrumadora. De forma inconsciente el cerebro se prepara para dar una respuesta efectiva, sacando los recursos de afrontamiento aprendidos para recuperar el equilibrio.
                  
              .tarjeta.color-acento-botones.p-4(x="29%" y="82%" numero="+" style='border-radius: 10px; background-color: #FFE8C8')
                h5.mb-3.text-center Respuesta desorganizada
                p.mb-0.text-center Hay aumento de la tensión y las respuestas emocionales y cognitivas fallan para enfrentar la crisis de forma adecuada. Las respuestas  se tornan confusas y  provocan  disfunciones.
                  
              .tarjeta.color-acento-botones.p-4(x="47.5%" y="7%" numero="+" style='border-radius: 10px; background-color: #FFE8C8')
                h5.mb-3.text-center Explosión
                p.mb-0.text-center Se pierde el control de las emociones, los pensamientos y los comportamientos tienden a ser contradictorios. Las reacciones pueden pasar de pasivas a agresivas durante semanas.
                  
              .tarjeta.color-acento-botones.p-4(x="66%" y="90%" numero="+" style='border-radius: 10px; background-color: #FFE8C8')
                h5.mb-3.text-center Estabilización
                p.mb-0.text-center Inicia la calma a medida que aparecen los recursos alternos. La persona es muy vulnerable en este momento y puede volver a la fase de explosión. Hay cierto nivel de conciencia de lo que ha sucedido, pero las reacciones ya no son tan extremas.
                  
              .tarjeta.color-acento-botones.p-4(x="84.5%" y="8%" numero="+" style='border-radius: 10px; background-color: #FFE8C8')
                h5.mb-3.text-center Adaptación
                p.mb-0.text-center Comienza el proceso de control sobre las acciones, puede concentrarse en otras situaciones, además del evento vivido, orienta interés por el futuro, se reactiva la socialización y puede descubrir nuevos rumbos a partir de la experiencia vivida.

            .row.justify-content-center
              .col-auto
                a.anexo(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-doc.svg")
                  .anexo__texto
                    p Formato instruccional - muestra      

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        ImagenInfografica.color-acento-botones.mb-5(data-aos="fade-left")
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/infografia/infografia_02.png')              

          .tarjeta.color-acento-botones.p-3(x="1%" y="55%" numero="+")
            p.mb-0 La raíz el cual se encarga de fijarse al suelo, el medio por el cual absorbe agua y los minerales que son necesarios para elaborar su propio alimento, la raíz está conformada por cuello, raíz principal, pelos absorbentes y cofia.
          .tarjeta.color-acento-botones.p-3(x="15%" y="55%" numero="+")
            p.mb-0 Las flores son los órganos reproductivos y de allí se generan después los frutos y las semillas, las flores se componen de estambre y pistilos, pero también encontramos flores que nunca florecen. 
          .tarjeta.color-acento-botones.p-3(x="25.5%" y="55%" numero="+")
            p.mb-0 Las semillas se producen después de la fecundación de la flor algunas semillas tienen carnosidad como frutos, y los frutos son recubrimientos carnosos o secos de la semilla casi siempre son nutritivas y de consumo para los seres vivos.
          .tarjeta.color-acento-botones.p-3(x="47%" y="75%" numero="+")
            p.mb-0 El tallo es la parte aérea la cual sostiene sus otros órganos vegetales, este crece en sentido opuesto a la gravedad, se encuentran diferentes tipos de tallos pero esto depende del medio en el que se desarrolle siendo así subterráneos o aéreos y su función consiste en sostener toda la planta, transportar los nutrientes por el interior de la planta.
          .tarjeta.color-acento-botones.p-3(x="87%" y="55%" numero="+")
            p.mb-0 Las hojas tienen diferentes forman y nacen del tallo son las encargadas de realizar la fotosíntesis, por lo general se caen cuando hace mucho frío para prevenir la pérdida de agua del árbol.   

      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 3")
        .row.justify-content-center.align-items
          .col-lg-10.mb-3
            ImagenInfografica.color-acento-botones
              template(v-slot:imagen)
                figure
                  img(src="@/assets/curso/temas/infografia/infografia_03.svg", alt= "")
              .tarjeta.color-acento-botones.p-3(x="36.3%" y="28%" numero="1")
                h4 1. Precipitación
                p.mb-0 Se produce por la condensación del vapor de agua liberado en la atmósfera, cuyas partículas al pasar al estado líquido alcanzan su punto de saturación, colisionan, se adhieren y ganan peso hasta que se precipitan por acción de la gravedad. 
              .tarjeta.color-acento-botones.p-3(x="10%" y="78%" numero="2")
                h4 2. Infiltración
                p.mb-0 Corresponde al fenómeno mediante el cual el agua de escorrentía penetra en el subsuelo para alimentar los sistemas acuíferos. 
              .tarjeta.color-acento-botones.p-3(x="28%" y="72%" numero="3")
                h4 3. Escorrentía
                p.mb-0 El agua dulce que cae en estado sólido o líquido escurre a través de la superficie terrestre en forma de quebradas o ríos hasta llegar al mar o alimentar los acuíferos subsuperficiales. 
              .tarjeta.color-acento-botones.p-3(x="60%" y="36%" numero="4")
                h4 4. Evaporación
                p.mb-0 Transformación del agua en vapor de agua por efecto de la radiación solar. 
              .tarjeta.color-acento-botones.p-3(x="92.7%" y="36%" numero="5")
                h4 5. Transpiración
                p.mb-0 Acción por medio de la cual las plantas, a través de sus estomas, liberan agua a la atmósfera en forma gaseosa.    

    #t_2_2
    h3.mb-5 2.2 Infografía interactiva - modales #[i.fas.fa-angle-double-left.txt--orange.ms-2]

    TabsA.color-acento-botones.mb-5    
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 1")
        .row.justify-content-center
          .col-lg-11
            ImagenInfograficaB.color-primario.mb-5
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/infografia/infografia_05.png', alt='Texto que describa la imagen')

              div(x="0%" y="5%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Ganado bovino
                      p.mb-3  Es tal vez una de las explotaciones pecuarias más difundida en el mundo y se dedica principalmente a la producción de carne y leche. Se efectúa en sistemas intensivos, semiintensivos y extensivos en múltiples condiciones agroecológicas.
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_01.png', alt='imagen decorativa')

              div(x="0%" y="23%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Porcinos
                      p.mb-3  La producción porcícola se desarrolla en múltiples climas y altitudes, en sistemas que pueden ser extensivos e intensivos.
                      p.mb-3  Estas explotaciones se orientan principalmente a la producción de carne, con destino al consumo directo y a la industria. Igualmente, es común la producción de lechones.
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_02.png', alt='imagen decorativa')

              div(x="0%" y="40%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Avícola
                      p.mb-3  Esta es una de las industrias más grandes que existen en el mundo, pues es una de las proteínas de origen animal más consumidas. En la industria avícola destacan la producción de huevo, pollo de engorde y pollo de levante.
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_03.png', alt='imagen decorativa')

              div(x="0%" y="55%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Búfalos
                      p.mb-3  La producción de carne y leche de búfalo se desarrolla, principalmente, en zonas de trópico bajo, donde se dan condiciones de alta temperatura. Son una fuente importante de proteína. 
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_04.png', alt='imagen decorativa')

              div(x="0%" y="70%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Equinos
                      p.mb-3  A este grupo pertenecen, principalmente, caballos, asnos y mulares. Estos animales se utilizan a menudo como apoyo en las labores del campo, en el deporte, las exposiciones, la producción de genética, la recreación y la producción de carne. 
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_05.png', alt='imagen decorativa')                    

              div(x="0%" y="88%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Ovinos
                      p.mb-3  Es uno de los sistemas de ganadería más antiguos y conocidos del mundo. Estos animales, por lo general, se destinan para la obtención de carne, especialmente los camuros, y lana, como en el caso de las ovejas. Estos animales poseen un amplio rango de adaptación climática. 
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_06.png', alt='imagen decorativa')    

              div(x="100%" y="5%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Caprinos
                      p.mb-3  Junto con los ovinos, los caprinos también pertenecen al grupo de los pequeños rumiantes y son una de las explotaciones pecuarias más populares debido a su gran capacidad adaptativa. En este grupo se destaca la producción de cabras doble propósito. 
                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_07.png', alt='imagen decorativa')   

              div(x="100%" y="23%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Otras aves
                      p.mb-3  Además del pollo de engorde y la gallina ponedora, existen otras aves que igualmente se consideran de importancia económica debido a su participación en el ámbito comercial. 
                      p.mb-3  Entre estas se encuentran pavos, patos, codornices, gansos, palomas y aves ornamentales. Estos animales se encuentran en múltiples rangos de altitud y temperatura, lo cual resulta muy favorable desde el punto de vista técnico. 

                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_08.png', alt='imagen decorativa')   


              div(x="100%" y="40%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Otras especies menores
                      p.mb-3  Dentro de este grupo de especies menores destacan actividades productivas como la cunicultura y la producción de cuy. 
                      p.mb-3  Estos animales se constituyen en fuente importante de alimento a muy bajo costo. Además de la carne, su piel también es aprovechable.

                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_09.png', alt='imagen decorativa')   

              div(x="100%" y="55%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Peces
                      p.mb-3  Este es otro de los grandes grupos de especies animales capaces de constituir proyectos productivos con altos niveles de rentabilidad. 
                      p.mb-3  Este tipo de proteínas tienen una alta demanda en diversos espacios, además que estos montajes se adaptan a diversas condiciones agroecológicas.

                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_10.png', alt='imagen decorativa')   

              div(x="100%" y="70%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Especies no convencionales
                      p.mb-3  Recientemente, algunas especies animales han empezado a adquirir relevancia en el escenario productivo debido a su potencial alimenticio. 
                      p.mb-3  Dentro de este grupo destacan reptiles como iguanas, babillas y tortugas hicoteas. También existen explotaciones de caracoles, avestruces, llamas y alpacas. 

                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_11.png', alt='imagen decorativa')   

              div(x="100%" y="88%" tooltip="Ver más" numero="+")
                .tarjeta.white-card.p-4
                  .row
                    .col-lg-7
                      .h4 Insectos y anélidos
                      p.mb-3  Existen iniciativas de cría de mariposas con fines ornamentales; explotación apícola para la obtención de miel y polen, larvas de gusano de seda, lombriz roja californiana para la producción de proteína animal o para la transformación de los subproductos de la industria agropecuaria.

                    .col-lg-5
                      figure
                        img(src='@/assets/curso/temas/infografia/mod_12.png', alt='imagen decorativa') 

            .row.justify-content-center
              .col-auto
                a.anexo(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-doc.svg")
                  .anexo__texto
                    p Formato instruccional - muestra

              
      .tarjeta.color-acento-botones--borde.p-4(titulo="Ejemplo - 2")
        .row.justify-content-center
          .col-12
            ImagenInfograficaB.color-acento-botones.custom
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/temas/infografia/infografia_04.svg', alt='')             

              div(x="27.1%" y="45.3%" tooltip="Creación y captura" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Creación y captura
                    p Corresponde a la primera etapa del ciclo de vida de la información. Los datos pueden surgir a partir de diversas fuentes, siempre y cuando, las mismas se encuentren destinadas a suplir las necesidades de la organización. Algunas de las fuentes de información más utilizadas son las siguientes:
                    ul.lista-ul--separador
                      li 
                        i.fas.fa-angle-right
                        | Datos preexistentes
                      li 
                        i.fas.fa-angle-right
                        | Generación de la información
                      li 
                        i.fas.fa-angle-right
                        | Información disponible                 
    
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_05.png", alt="alt", style="width:400px;").m-auto

              div(x="27.1%" y="57%" tooltip="Datos preexistentes" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Datos preexistentes
                    p Pueden ser de otras organizaciones, empresas que pueden dedicarse al mismo sector o a la misma actividad, puesto que, de esta forma, se posibilita la homologación de los datos entre compañías, sin esfuerzos desproporcionados.   
    
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_06.png", alt="alt", style="width:400px;").m-auto

              div(x="27.1%" y="70%" tooltip="Generación de la información" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Generación de la información
                    p A través de las actividades desarrolladas por los funcionarios encargados.   
    
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_07.png", alt="alt", style="width:400px;").m-auto

              div(x="27.1%" y="83%" tooltip="Información disponible" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Información disponible
                    p En medios de acceso público, como libros, noticiarios, páginas web o redes sociales; la selección de estas fuentes estará supeditada a la naturaleza de la investigación y sus objetivos. 
    
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_08.png", alt="alt", style="width:400px;").m-auto

              div(x="44.3%" y="45.3%" tooltip="Transmisión, almacenamiento y seguridad" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Transmisión, almacenamiento y seguridad
                    p Una vez la información ha sido recolectada, se continúa con la transmisión a los usuarios interesados. Para garantizar el acceso a los datos en periodos posteriores, es necesario su almacenaje en condiciones seguras que garanticen su integridad.   
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_09.png", alt="alt", style="width:400px;").m-auto

              div(x="44.3%" y="57%" tooltip="Transmisión" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Transmisión 
                    p La información puede ser relevante para diferentes actores en una misma organización. Los datos de venta son importantes para el área comercial, pero también lo son para el área de recaudo o de producción. Debido a esto, deben existir medios de transmisión de la información que permitan que esta llegue a todos los interesados. Las posibilidades van desde las soluciones integrales asociadas a softwares administrativos, hasta los programas de mensajería instantánea.  
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_10.png", alt="alt", style="width:400px;").m-auto

              div(x="44.3%" y="70%" tooltip="Almacenamiento" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Almacenamiento 
                    p Tanto la información física como digital demandan espacios para su almacenamiento. Las bases de datos abordan esta tarea conservando la información según los criterios técnicos aplicados, de la misma forma que lo hace una estantería que archiva los documentos físicos.   
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_11.png", alt="alt", style="width:400px;").m-auto

              div(x="44.3%" y="83%" tooltip="Seguridad" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Seguridad
                    p Cuando se trabaja con datos sensibles, deben existir sistemas encargados de facilitar la información a aquellos destinatarios cuando la requieran, pero de esta misma forma, deben implementarse medidas para que el acceso sea lo suficientemente controlado para evitar que personas no autorizadas accedan a ella. La información es un activo intangible de vital importancia para cualquier organización, puesto que compila datos variados y claves de la empresa, como clientes, fórmulas de producción o estrategias mercantiles; su publicación puede conllevar consecuencias graves, donde se pierden ventajas competitivas.   
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_12.png", alt="alt", style="width:400px;").m-auto

              div(x="61.2%" y="45.3%" tooltip="Gestión y trabajo colaborativo" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Gestión y trabajo colaborativo
                    p Debido a las diversas perspectivas desde donde se puede abordar la información, suele ser recomendable el trabajo colaborativo. Cuando existe multiplicidad de colaboradores, la productividad incrementa; es por ello que, usualmente, se designan funcionarios de cada área para sustraer los datos más relevantes para ellos, otorgando los permisos necesarios en una ventana de tiempo determinada.   
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_13.png", alt="alt", style="width:400px;").m-auto

              div(x="78.3%" y="45.3%" tooltip="Análisis y explotación de datos" numero="+")
                .row.justify-cotent-center.align-items-center
                  .col-lg-8
                    h5 Análisis y explotación de datos
                    p La interpretación de la información se erige como la última fase de su ciclo de vida, y es en este proceso donde se genera nuevo conocimiento a partir de los datos recolectados. El análisis busca llegar a conclusiones o juicios de valor fundamentados, por lo que la toma de decisiones debe darse una vez se aborda este apartado.   
                  .col-lg-4
                    figure
                      img(src="@/assets/curso/temas/infografia/t1_13.png", alt="alt", style="width:400px;").m-auto

      
    

</template>

<script>
export default {
  name: 'Tema2',
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

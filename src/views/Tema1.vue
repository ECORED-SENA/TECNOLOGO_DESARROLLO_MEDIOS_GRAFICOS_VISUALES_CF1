<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Definición e historia del diseño gráfico
    p.mb-5 El diseño gráfico puede definirse como una disciplina que interactúa, por lo general, con muchas otras disciplinas en diversos ámbitos y que busca la solución a problemas de comunicación visual, para dar a conocer, exponer y publicitar diversos productos, bienes y servicios, por medio de diferentes piezas gráficas que pretenden transmitir un mensaje específico.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        p.mb-3 Es así como se produjeron numerosos inventos que transformaron la sociedad y, junto con otros avances técnicos, potenciaron la prensa como fenómeno de masas y clases sociales. Se crearon espacios de ocio, como clubes, teatros y salones de reunión, donde se necesitaron piezas gráficas y publicidad. La invención de estos medios de comunicación, sumada a inventos como el de Joseph Niepce, quien, en 1826, fijó una imagen en una cámara oscura, invento que posteriormente Louis Daguerre perfeccionó en los llamados daguerrotipos (primer procedimiento fotográfico), fueron el inicio de una época que revolucionaría a la humanidad.
        .bg--4-claro.p-3.px-5
          p.mb-0 El diseño sigue su avance tanto en Europa como en Estados Unidos, ejes importantes y vitales en su desarrollo. En Europa, se sigue una línea clásica y muy estructurada, mientras, en Estados Unidos, el diseño se vuelve moderno y novedoso en los conceptos, tratando de dar solución a diversas necesidades. De los más conocidos diseñadores por su trabajo están Paul Rand y Saul Bass.
      .col-lg-5.mt-lg-0.mt-3(data-aos="fade-left")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/1.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
    p.mb-5 Pasadas las décadas, surgieron movimientos juveniles y opositores del sistema. El diseño toma un rumbo de tintes rebeldes, que, unido a medios como la televisión, la fotografía, la fotocomposición realizada en los nuevos programas de cómputo, gana forma y se plasma de maneras diferentes. Nace entonces la era digital, donde se desarrollan múltiples programas, herramientas y artefactos, que nos permiten trabajar con mayor agilidad y libertad las herramientas del diseño. 
      br
      br
      | Algunos representantes en la historia del diseño gráfico son: 
    .infografia-autores.p-5
      img(src="@/assets/curso/2.svg" alt="Adornos flotantes")
      .infografia-autores__img(@mouseover="mostrarIndicador = false")
        img(src="@/assets/curso/3.png" style="left: 44.3% ; right:  ; top: 13.5% ; bottom:  ; width: 14.6% ")
        .indicador--hover(v-if="mostrarIndicador" style=" top: 19% ")
      .infografia-autores__img: img(src="@/assets/curso/4.png" style="left: 22% ; right:  ; top: 25% ; bottom:  ; width: 14.6% ")
      .infografia-autores__img: img(src="@/assets/curso/5.png" style="left: 66.9% ; right:  ; top: 25% ; bottom:  ; width: 14.6% ")
      .infografia-autores__img: img(src="@/assets/curso/6.png" style="left: 16.2% ; right:  ; top: 50% ; bottom:  ; width: 14.6% ")
      .infografia-autores__img: img(src="@/assets/curso/7.png" style="left: 72.2% ; right:  ; top: 50% ; bottom:  ; width: 14.6% ")
      .infografia-autores__img: img(src="@/assets/curso/8.png" style="left: 31.7% ; right:  ; top: 70.9% ; bottom:  ; width: 14.6% ")
      .infografia-autores__img: img(src="@/assets/curso/9.png" style="left: 57.1% ; right:  ; top: 70.9% ; bottom:  ; width: 14.6% ")
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.1 Arte vs. diseño
    p.mb-5 Tanto el arte como el diseño hacen parte del mundo circundante y suelen ser confundidos, pues aparentemente son muy similares. La siguiente tabla busca mostrar especialmente sus diferencias.
    .titulo-sexto.color-acento-contenido
      h5 Tabla 1
      span Diferencias entre arte y diseño
    .tarjeta.bg--2.p-5.mb-5
      .row.mb-5.justify-content-between.g-0
        .col-lg-6
          h3.m-auto.text-center.mb-3 Arte
          SlyderF.tarjeta-h(columnas=" col-xl-12")
            .tarjeta.bg-white.p-4
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El arte es espontáneo y se genera a partir de expresar un sentimiento, una idea o un pensamiento; es la solución a una inquietud o pregunta interior del artista.  
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El artista genera su propia historia.
            .tarjeta.bg-white.p-4.h-100 
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Requiere de la aprobación del autor. 
            .tarjeta.bg-white.p-4.h-100 
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Cada persona interpreta el arte desde su propia óptica.
            .tarjeta.bg-white.p-4.h-100 
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El mensaje es libre de interpretaciones.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/10.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El uso de materiales es muy libre, se pueden utilizar a selección del autor.
        .col-lg-6
          h3.text-center.mb-3 Diseño
          SlyderF.tarjeta-h(columnas=" col-xl-12")
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El diseño busca la solución a un problema o necesidad, tiene un objetivo específico.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El diseñador basa su trabajo en elementos consignados generalmente en un brief, el cual es un documento informativo donde se encuentran instrucciones específicas para llevar a cabo su labor. 
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El diseñador parte de la necesidad de un cliente, que tiene un producto, marca o empresa ya existente; y hace su aporte para crear, mejorar o exaltar los atributos de este.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Requiere de la aceptación por parte de un grupo, cliente, empresa o entidad.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Hay un público objetivo a quién va dirigido el mensaje, por eso se estudia muy bien al receptor.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Hay un público objetivo a quién va dirigido el mensaje, por eso se estudia muy bien al receptor.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center Busca generar en la población un mensaje particular, implantar una idea o concepto, lo cual genera en el diseñador una responsabilidad tanto ética como moral.
            .tarjeta.bg-white.p-4.h-100
              .row.justify-content-center.mb-3
                .col-8
                  img(src='@/assets/curso/11.svg' alt='AvatarTop' style='width: 190px').m-auto
              p.text-center El diseñador está sujeto a la funcionalidad, utilidad y practicidad de los materiales que utiliza.
      .row.justify-content-center.mb-3.g-0
        .col-lg-4
          .bg--4.p-4.text-center.h-100.d-flex.align-items-center
            h5.text-center.mb-3 El arte y el diseño poseen varias orientaciones disciplinarias.  
        .col-lg-4
          .bg--4.p-4.text-center.h-100.d-flex.align-items-center
            h5.text-center.mb-3 En los dos, influye la creatividad, la capacidad para crear o inventar algo.
        .col-lg-4
          .bg--4.p-4.text-center.h-100.d-flex.align-items-center
            h5.text-center.mb-3 Sus aportes perduran en el tiempo.
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.2 Historia del arte
    p.mb-5 La historia del arte <b>es la disciplina de las ciencias sociales encargada de estudiar la evolución del arte a través de cada etapa del tiempo</b>, basando sus estudios en la clasificación y observación de culturas, pueblos y civilizaciones. Su campo de exploración permite identificar cómo el hombre ha evolucionado a través de los tiempos y cuál era su visión respecto al mundo que lo rodeaba en cada etapa desde su existencia. Su estudio requiere ayuda de otras múltiples disciplinas, como arqueología, antropología, geografía, historia y otras más. 
      br
      br
      |Por medio de la historia, se pueden identificar aspectos importantes en las sociedades, como cultura, creencias, política, costumbres, agricultura, vestimenta y muchas más.
      br
      br
      b Las principales etapas de la historia del arte las podrá ver de una manera más detallada a continuación: 
    .row.justify-content-center.mb-3.g-0
      .col-lg-10     
        figure.mb-5(data-aos="zoom-in-up")
          img(src='@/assets/curso/12.svg' alt='AvatarTop').m-auto
    .texto-adorno.bg--2.px-4.py-2.mb-5(data-aos="fade-right")
      h4.mb-0.me-3 Prehistoria
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        p 
          b Paleolítico (2,5 millones a 10.000 a. C.)
          br
          br
          |La palabra paleolítico significa “piedra antigua”, es un periodo que empieza con la vida misma del ser humano. Durante este periodo, el hombre empieza a desarrollar herramientas útiles con diversos materiales, como piedras, maderas, huesos tallados y demás elementos que encontraba en la naturaleza. Aparecen varias técnicas agrícolas y se dice que durante este periodo se hace el descubrimiento del fuego, descubrimiento de gran importancia para todos los periodos venideros.
      .col-lg-5(data-aos="fade-left")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/14.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
    p.mb-5 El periodo se divide en tres fases: <b>paleolítico inferior, paleolítico medio, paleolítico superior</b>. A continuación podrá profundizar estas fases con mayor detenimiento:
    SlyderD.mb-5(:datos="datosSlyder")
    .texto-adorno.bg--2.px-4.py-2.mb-5(data-aos="fade-right")
      h4.mb-0.me-3 Edad Antigua
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        p Esta parte de la historia se caracteriza por varios avances que, al igual que en el periodo neolítico, son fundamentales en el desarrollo y trascender de la humanidad. Si bien es cierto que el hombre desde el paleolítico ya dejaba su huella en las cuevas de Altamira, la escritura no se había desarrollado hasta ese momento. El desarrollo de los pueblos y la necesidad de comunicarse hacen que se manifiesten otras formas de comunicación diferentes a la expresión oral. 
        .tarjeta.color-acento-botones.p-4.mb-5.rounded-0.mt-5
          .row.justify-content-around.align-items-center.position-relative
            img.position-absolute.d-none.d-lg-block(src="@/assets/curso/21.svg" alt="Adornos flotantes" style="width: 75px ; left: 3% ; top: -80% ")
            .col-4.col-sm-2.col-lg-1
            .col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small.text-white.mb-0 A través del siguiente video, podrá revisar todo lo que compone esta parte de la historia para el diseño gráfico:
                .col-sm-auto
                  a.boton.color-acento-contenido(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      .col-lg-5(data-aos="fade-left")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/20.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 30% ; right: ; top:-10% ; bottom: ; width: 40px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
    .texto-adorno.bg--2.px-4.py-2.mb-5(data-aos="fade-right")
      h4.mb-0.me-3 Edad Media 
    p.mb-5 Esta edad se compone de diversos tipos de arte:
    .row.mb-5.justify-content-center.g-4
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-primario.rounded-0(@mouseover="indicadorTarjetaSlide = false" style=' height: 275px')
          .indicador--hover(v-if="indicadorTarjetaSlide")
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5.m-auto
              img(src="@/assets/curso/26.svg" style="width: 130px").m-auto.mb-3
              h4.text-center El arte bizantino
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/22.jpg')})`}")    
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.abajo.color-secundario.rounded-0( style=' height: 275px')
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5.m-auto
              img(src="@/assets/curso/27.svg" style="width: 130px").m-auto.mb-3
              h4.text-center El arte románico
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/23.jpg')})`}")    
      .col-sm-6.col-xl-3.mb-4.mb-xl-0
        .tarjeta.tarjeta-slide.arriba.color-primario.rounded-0(style=' height: 275px')
          .tarjeta-slide__contenedor
            .tarjeta-slide__contenido.p-4.p-xl-5.m-auto
              img(src="@/assets/curso/28.svg" style="width: 130px").m-auto.mb-3
              h4.text-center El arte gótico 
            .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/24.jpg')})`}")
    p.mb-5 Conozca más acerca de estos tipos de arte a continuación:   
    SlyderE(indicadores="izquierda").mb-5 
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte bizantino
          p La palabra bizantino corresponde al Imperio Romano de oriente, cuya capital era Bizancio, en el periodo comprendido entre el 395 y el 1454, año en que Constantinopla fue tomada por los turcos. El emperador Constantino pretendió consolidar la unidad política, trasladando la capital imperial de Roma a Bizancio, que era una ciudad griega en los límites entre Europa y Asia. Hoy se conoce como Estambul. Pero en el año 395, el emperador Teodosio dividió el imperio, separando el mundo latino del griego. Luego de enfrentar la invasión germánica, solamente las provincias de oriente continuaron el legado cultural romano, fundiéndose con la cultura helenística. En ese momento, el imperio era teocrático, con un solo Dios y una sola autoridad, el emperador, quien estaba encargado de defender y propagar la fe; sin embargo, la división del imperio produjo también la división religiosa: en oriente, eran ortodoxos y en occidente, cristianos. Esta situación produjo también cambios en el arte, debido a su ubicación privilegiada entre Europa y Oriente.
      
        .col-md-6
          figure
            img(src='@/assets/curso/29.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte bizantino
          p La pintura en este periodo representa el absoluto influjo de la religión en la vida social y política del Imperio Oriental, pero a comienzos del año 730, bajo la autoridad del emperador León III, surgió una crisis iconoclasta que duró hasta el siglo IX, cuando se prohíbe la elaboración de imágenes religiosas en el Imperio, ya que se consideró que dichas imágenes conducían a la idolatría, porque en la materia estaba lo maligno y, por lo tanto, no contribuían en el propósito de seguir el camino a lo divino. Por esa razón, los mosaicos fueron cubiertos dentro de los templos, los motivos religiosos se reemplazaron por retratos del emperador, escenas de guerra, de carreras de caballos o de caza, vegetales o animales.
            br
            br
            |Luego vino el cisma entre las iglesias de Constantinopla y Roma, entonces las imágenes volvieron a ser admitidas en los templos, pero con un valor sagrado, rindiendo culto a Dios por medio de ellas.
      
        .col-md-6
          figure
            img(src='@/assets/curso/30.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte románico
          p Surge en el siglo X y se extiende hasta el XII. En el siglo X, el emperador Otón, junto con Carlomagno, quien gobernó en el siglo IX, fijó las bases de la Europa feudal, caracterizada por el feudo y la dependencia de los vasallos respecto a su señor. En el centro de la propiedad, que era una enorme extensión de tierra, estaba el castillo, la catedral o la abadía. El poder dependía de la cantidad de tierras que se poseyera, y en la cúspide social estaba el rey. En esa época, la iglesia católica logró la unidad de Europa; pero la Iglesia estaba manejada por el poder civil, pues los obispos eran nobles a quienes los reyes u otros nobles les entregaban sus diócesis; en correspondencia, la institución del papado se fortaleció. Los monjes se dedicaron a realizar trabajos manuales, tareas agrícolas y artesanales, convirtiéndose los monasterios benedictinos en centros económicos independientes y en focos culturales de primera importancia, ya que copiaban manuscritos antiguos, realizaban pinturas de miniaturas y redactaban crónicas históricas. 
      
        .col-md-6
          figure
            img(src='@/assets/curso/31.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte románico
          p En cuanto a la arquitectura románica, se caracteriza por las iglesias en forma de cruz latina; usualmente, tienen una cripta en la que se depositaban los cuerpos de los santos. En esta época, se retomaron materiales y técnicas de construcción de los romanos, también se construyeron campanarios. La arquitectura tenía un significado religioso, por eso la escultura románica es monumental, y estas obras, como iban dirigidas a los fieles y los peregrinos, se ubicaban en las portadas de las iglesias, dentro de ellas y en los conventos. Las imágenes tienen como protagonista a Cristo. Utilizaron la decoración geométrica, vegetal, humana o animal, dispuesta en sentido radial. En las columnas también esculpieron estatuas; las representaciones, en general, eran religiosas, relacionadas con diferentes pasajes de la Biblia, por ejemplo, los cuatro evangelistas, el juicio final y otros. La ubicación de las imágenes dentro de las iglesias se hacía por orden jerárquico y de importancia, por ejemplo, en el norte está el antiguo testamento, el sur es el nuevo y el oeste el juicio final. Las pinturas murales se ubicaron en el ábside o parte posterior del altar. 
      
        .col-md-6
          figure
            img(src='@/assets/curso/32.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte gótico
          p Se inició en el siglo XII, alcanzando su esplendor en los siglos XIII al XV. Los cambios en la sociedad produjeron el desplazamiento de los campos hacia las regiones urbanas, donde dominó la burguesía, clase fundamentalmente comerciante, que propendió por el sentido comunal, la defensa de los intereses de sus habitantes y la autonomía municipal. Por esa razón, al lado del poder religioso representado en las catedrales, se construyeron los ayuntamientos. Los artesanos y los artistas se organizaron en gremios que buscaban evitar la competencia y el monopolio. Los gremios se encargaron de realizar numerosas obras artísticas, siendo la ciudad un polo de desarrollo cultural, sobre todo por el surgimiento de las universidades, que desplazaron a los monasterios. en la arquitectura gótica se utilizó el vidrio con tonos preferencialmente azules y rojos, y la piedra en forma de sillares, por cuanto lo estructural tuvo para la época enorme valor estético.
      
        .col-md-6
          figure
            img(src='@/assets/curso/33.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte gótico
          p Hasta el siglo XIV en Italia y en el siglo XV en Flandes, la pintura se desarrolló más tarde que la arquitectura y la escultura. En Italia, la pintura tenía influencia bizantina, manteniendo un estilo idealista, con curvas delicadas, fondos dorados y cuerpos alargados, conservando la mayor parte de los descubrimientos helenísticos que pasaron a la edad media. Pero las demandas de la burguesía adinerada exigían más obras pictóricas realistas, en las que se reprodujera el mundo visible aplicando el naturalismo de los escultores góticos. Pintaron especialmente figuras en un espacio que representara profundidad. Giotto utilizó el fresco con dominio completo, introdujo la tercera dimensión, lo que consiguió a través del escorzo y el juego entre luces y sombras, y el fondo antes dorado lo sustituyó por el cielo y el paisaje. Giotto se hizo famoso, hecho que era nuevo, pues hasta el momento las obras de arte eran anónimas, y se convirtió en el precedente de la perspectiva, que fue la gran conquista del Renacimiento. 
      
        .col-md-6
          figure
            img(src='@/assets/curso/34.jpg', alt='Texto que describa la imagen')
      .row
        .col-md-6.mb-4.mb-md-0
          h4 El arte gótico
          p En cuanto a Flandes, se produjo una renovación en la pintura, inclinándose hacia la realidad partiendo de la observación, incorporando todos los detalles posibles, utilizando el claroscuro, lo cual hizo ganar en profundidad y volumen a las obras, dando mayor apariencia de vida. Utilizaron el óleo, cubierto al final con una capa de barniz. Esta técnica pictórica permite desarrollar el estilo flamenco, pintando imágenes religiosas y el retrato de los burgueses flamencos, quienes preferían pinturas en caballete por ser más fáciles de transportar. En ese momento histórico, Italia ya se encaminaba al Renacimiento.
      
        .col-md-6
          figure
            img(src='@/assets/curso/35.jpg', alt='Texto que describa la imagen')
    .texto-adorno.bg--2.px-4.py-2.mb-5(data-aos="fade-right")
      h4.mb-0.me-3 Edad Moderna
    h5(data-aos="fade-right") Renacimiento
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5(data-aos="zoom-in-up")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/36.jpg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Fue el nombre que se le dio a un importante movimiento filosófico y artístico que se produjo en Europa desde finales del siglo XIV hasta el siglo XVI, y fue una etapa de transición de la Edad Media a la Era Moderna. Su principal desarrollo se produjo en Italia. Su denominación se debe a que en esta época se redescubrieron la cultura greco-romana y la filosofía clásica. Se inspiró en la olvidada cultura de la Edad Media, el racionalismo, la experimentación, y también en la exaltación de la naturaleza humana, pues el hombre fue el centro del universo, la medida de todas las cosas. 
    p.mb-5 A medida que más personas aprendían a leer y que los libros se imprimieron y llegaron a sitios geográficos diversos, gracias al invento de la <b>imprenta, creación de Johannes Gutenberg,</b> la capacidad de raciocinio generó una revolución intelectual en la búsqueda del conocimiento, pues la difusión de textos propendía por la renovación cultural y por la reinterpretación de los valores tradicionales greco-romanos. Los cambios se dieron gradualmente y afectaron a toda la sociedad en todos los aspectos. 
      br
      br
      |Durante el Renacimiento, los artistas firmaron sus obras y la burguesía compraba imágenes o estatuas de sí mismos, formando parte del hedonismo que caracterizó la época. Los artistas eran realistas, porque integraban al hombre con la naturaleza, la creación y el universo, y dependían económicamente de mecenas (patrocinio que se otorgaba a los artistas), quienes eran comerciantes, banqueros, aristócratas, incluso Papas.
    .row.mb-5.justify-content-center.g-0.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/37.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p.ms-5 El auge de El Renacimiento fue entre 1490 y 1527, y en cuanto a la arquitectura, Filippo di Ser Brunellesco Lapi fue el más destacado, también fue escultor y orfebre. Otro destacado representante del Renacimiento fue Michelangelo Buonarroti, quien era arquitecto, escultor y pintor, caracterizado por su perfeccionismo en la escultura y en la pintura (realizó la obra excepcional de la bóveda de la Capilla Sixtina por imposición del Papa Julio II), elaboró esculturas muy importantes, como La Piedad y El David. Asimismo, <b>Leonardo Da Vinci fue considerado el último hombre de El Renacimiento</b>, fue un gran polímata (persona que se destaca en diferentes disciplinas), tuvo creaciones relacionadas con el helicóptero, el submarino, entre otras. Sus obras más representativas son La Gioconda y La Última Cena.
        .bg--1-claro.p-3.ps-5
          p.mb-0 <b>Retrato de Lisa Gherardini</b>, esposa de Francesco del Giocondo, obra conocida como La Gioconda o La Mona Lisa. Actualmente, expuesta en el Museo del Louvre en París.
    h3(data-aos="fade-right") El Barroco
    .row.mb-5.justify-content-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/38.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p Expresaba una sensibilidad desengañada, crítica, compleja y pesimista. El término fue utilizado inicialmente para referirse a algo engañoso o recargado, en forma despectiva, pero desde el siglo XIX, el término se utilizó para referirse no sólo al periodo, sino a las manifestaciones artísticas que contradijeron los valores del clasicismo, mediante una negación simbólica y artística de lo clásico, por eso fue femenino, irracional y dionisíaco. El Barroco enfatizó lo cotidiano y efímero de la vida, lo cual produjo una vulgarización del imaginario religioso; consideró que lo nacional y religioso eran expresiones de poder político, por eso se elaboraron obras monumentales y recargadas, que propendían por hacer resaltar el poder dominante, pero mediante engaños y artificios.
    .row.mb-5
      .col-lg-8(data-aos="fade-right")
        .bg--1-claro.p-4
          p.mb-0 La pintura fue una expresión artística de El Barroco. Se distinguen dos vertientes, una naturalista, cuyo estilo se basa en la observación de la naturaleza, y la otra es el clasicismo, que es opuesta a la anterior, con un estilo más realista y racional, predominando el dibujo sobre el color; vertientes caracterizadas por el realismo superficial, los colores ricos, y el contraste entre las luces y las sombras. Exponentes de este período son Rembrandt, Rubens, Velásquez, Poussin, Vermeer y Caravaggio, quien realizaba una minuciosa observación anatómica con el uso del claroscuro, lo que otorgaba dramatismo a su obra y que llegó a conocerse como tenebrismo. Caravaggio plasmó vívidos momentos y escenas relacionadas con luchas violentas, muerte o tortura.
      .col-lg-4(data-aos="fade-left"): img(src="@/assets/curso/39.jpg" alt="Adornos flotantes")
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/40.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p La escultura barroca estuvo vinculada con la religión y con la arquitectura, porque decoraban los espacios públicos, los palacios y las locaciones religiosas. Eran dinámicas, expresivas y ornamentadas; expresaban pasiones y estaban recargadas de detalles. Se expresó en dos vertientes, una, la gótica, y otra, la renacentista. En términos generales, durante el período barroco, se siguieron trabajando los temas de historia, mitología y religión, aunque preferían las obras llenas de dramatismo. La Iglesia Católica prefirió los temas como la inmaculada concepción, la virgen, la eucaristía, los santos, asuntos claves en la disputa del protestantismo.
    .texto-adorno.bg--2.px-4.py-2.mb-5(data-aos="fade-right")
      h4.mb-0.me-3 Edad Contemporánea
    p.mb-5 Los avances tecnológicos que se aportaron en este época fueron de mucha trascendencia para la industria gráfica; los diferentes movimientos artísticos junto a sus representantes generaron la ruptura con la pintura tradicional, por lo que es importante que revise el siguiente video, pues le permitirá profundizar sobre el diseño gráfico que se marcó en esta época.
    .row.mb-5.justify-content-end.bg--2-claro.p-4.position-relative
      img.d-xl-block.d-none(src="@/assets/curso/41.svg" alt="Adornos flotantes" style="width: 136px; position: absolute; top: -20%; left: 5%;")
      .col-xl-10
        h4 Historia del diseño siglo XX
        p.mb-0 A continuación, observe el video Historia del diseño siglo XX para mejor contextualización sobre esta historia en la edad contemporánea.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video: Leyenda del video
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/42.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p Adicionalmente, es importante que sepa que el cubismo también se desarrolló en la escultura, con técnicas parecidas al collage del cubismo sintético, que integró señales y fragmentos de cosas reales. Se elaboró con materiales de desecho, compuestas de diversas piezas, con huecos y vacíos en la superficie. En la arquitectura, el cubismo no tuvo casi representación, se realizó sobre todo en Checoslovaquia, como en la Casa de la Virgen Negra de Praga.
    h3(data-aos="fade-right") Impresionismo
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/43.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p Este movimiento artístico se desarrolló a partir de la segunda mitad del siglo XIX en Europa, especialmente en Normandía. Propendía por plasmar la luz con la impresión visual en un instante determinado, gracias a la evolución y creación de nuevos pigmentos, que generaron gran variedad de colores, y como, además, los óleos venían en tubos, eso impedía que se secaran cuando pintaban al aire libre. Los pintores usaron colores puros, dando origen a la ley del contraste cromático, ya que todo color es relativo a los colores que le rodean, y a la ley de los colores complementarios. Contrastaron la luz con la oscuridad, generando la ilusión de profundidad por medio del modelado de color, que consiste en que por medio del color se crea volumen, con una zona de luz, de media sombra y sombra más profunda, agregando blanco para la luz y negro para la sombra.
    .bg--4-claro.p-4(data-aos="zoom-in-up").mb-5
      .row.justify-content-center.align-items-center
        .col-lg-2: img(src="@/assets/curso/44.svg") 
        .col-lg-8: p.mb-0 Para los pintores impresionistas, el dibujo y la forma pasaban a un segundo plano, siendo el reto más importante plasmar la iluminación y el color sobre el cuerpo o el objeto. Por eso, muchas imágenes se ven como diluidas o mezcladas. Buscaron iluminación interior, exterior, iluminación natural filtrada o al aire libre, con los reflejos sobre el agua, o la luz del sol a través de las hojas de los árboles.  
    h3(data-aos="fade-right") Neoclasicismo
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/45.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p Movimiento artístico con raíces filosóficas y estéticas de la antigüedad clásica, movimiento moralizante, social e intelectual, para adaptarse a la modernidad y reinterpretar sus formas, que surgió a mediados del siglo XVIII y se extendió hasta el XIX. Su furor se produjo debido al descubrimiento de Pompeya y Herculano, por lo que se realizaron numerosas expediciones para conocer las obras antiguas en sus lugares de origen. Además, apareció la Ilustración o el Iluminismo, que defendía la razón y el conocimiento para fomentar el progreso. Igualmente, tuvo lugar la Revolución Industrial, que modificó los modos de producción y organización social, y la Revolución Francesa, con sus proclamas de igualdad, libertad y fraternidad. 
    .bg--4-claro.p-4(data-aos="zoom-in-up").mb-5
      p.mb-0 El arte de este periodo tomó como temas modelos ideas morales de la historia grecolatina, la historia de las repúblicas y de la Revolución Francesa; elaboraron retratos y algunas pinturas religiosas. En cuanto a la pintura, el dibujo era de vital importancia, se usó el fresco, pero primordialmente el óleo; supresión de objetos decorativos. En cuanto a la anatomía, se utilizó lo impuesto por los clásicos antiguos, las pinceladas no se distinguen en las obras, la luz es clara y fría.
    .row.mb-5.justify-content-center.align-items-center
      .col-lg-5(data-aos="fade-right")
        .imagen-adornos-flotantes
          img(src="@/assets/curso/46.jpg" alt="Adornos flotantes")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: ; right: 10% ; top: ; bottom: 10% ; width: 90px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float5.png" style="left: 10% ; right: ; top:0 ; bottom: ; width: 60px ")
          .imagen-adornos-flotantes__img: img(src="@/assets/curso/float3.png" style="left: 15% ; right: ; top: ; bottom: 5% ; width: 60px ")
      .col-lg-7(data-aos="fade-left")
        p En cuanto a la escultura, se prefirió el mármol, el alabastro y el cobre, exaltando la belleza ideal y el equilibrio conforme a los clásicos antiguos; se dejó a un lado la policromía, que consistía en el arte de pintar o decorar con varios colores las obras; la representación de las emociones era sutil; las esculturas no son dinámicas.
    .tarjeta.bg--2-claro.p-4.mb-5.rounded-0.mt-5
          .row.justify-content-around.align-items-center.position-relative
            img.position-absolute.d-none.d-lg-block(src="@/assets/curso/47.svg" alt="Adornos flotantes" style="width: 117px ; left: 3% ; top: -80% ")
            .col-4.col-sm-2.col-lg-1
            .col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.text-small.mb-0 Para  reforzar sus conceptos en este tema, se le invita a ver el video <b>Cronología de la Historia del Arte que se encuentra en el material complementario.</b>
                .col-sm-auto
                  a.boton.color-acento-contenido(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                    span Enlace
                    i.fas.fa-link
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 1.3 Exponentes, movimientos y tendencias del diseño
    p.mb-5 Existen diversas tendencias y exponentes de cada periodo. Es importante aclarar que un mismo artista puede pertenecer a varias tendencias, ya que muchas de ellas se han dado en cortos periodos de tiempo.
      br
      br
      |Algunos de las tendencias del diseño son: 
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg--4-claro")
      .row(titulo="Art Nouveau").p-3
        .col-md-8.mb-4.mb-md-0
          p Finales del siglo XIX, principios del siglo XX
            br
            br
            | Este movimiento se caracteriza por tener grandes artistas en su lista. Uno de sus mayores expositores es Alfons Mucha, quien revolucionó con <b>su obra, la cual representaba la belleza y erotismo de la mujer, con gran delicadeza y sofisticación</b>. Mucha salta a la fama con la invención de un cartel para la obra Gismonda, protagonizada por la actriz Sarah Bernhardt, actriz de cine y teatro, muy importante en la movida parisina. Sarah fue la musa de varios de sus trabajos.
            br
            br
            |Este movimiento nace bajo las formas poéticas de la naturaleza, el manejo enriquecido de la línea, las curvas, fuerza y movimiento que pueden aportar, adaptándose a la vida moderna. Al igual que muchos otros movimientos, el Art Nouveau imprime su sello en todas las áreas artísticas de la época.
            br
            br
          h4 Caracteristicas
          ol.lista-ol--cuadro--color
            li 
              .lista-ol--cuadro__vineta
                span 1
              | Énfasis en elementos de la naturaleza, un estilo joven y moderno.
            li 
              .lista-ol--cuadro__vineta
                span 2
              | Manejo de la línea y las formas naturales.
            li 
              .lista-ol--cuadro__vineta
                span 3
              | Es el primer movimiento que trata de no parecerse a otro.
            li 
              .lista-ol--cuadro__vineta
                span 4
              | Se utilizaron gran cantidad de materiales, sobre todo en la arquitectura y el diseño industrial.
            li 
              .lista-ol--cuadro__vineta
                span 5
              | Énfasis rico en el color.
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
      .row(titulo="").p-3
        .col-md-8.mb-4.mb-md-0
          p 
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
      .row(titulo="").p-3
        .col-md-8.mb-4.mb-md-0
          p 
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
      .row(titulo="").p-3
        .col-md-8.mb-4.mb-md-0
          p 
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
      .row(titulo="").p-3
        .col-md-8.mb-4.mb-md-0
          p 
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
      .row(titulo="").p-3
        .col-md-8.mb-4.mb-md-0
          p 
        .col-md-4
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')



</template>

<script>
import BannerInterno from '../components/BannerInterno.vue'

export default {
  name: 'Tema1',
  components: {
    BannerInterno,
  },
  data: () => ({
    mostrarIndicador: true,
    datosSlyder: [
      {
        titulo: 'Paleolítico inferior',
        texto:
          'Es la etapa inicial de la historia de la humanidad, abarcó desde 3 millones de años atrás hasta el 250.000 a. C., tiene lugar en diferentes momentos y en diversas partes del mundo. Los humanos eran nómadas, cazadores y depredadores, se refugiaban en cavernas para protegerse del frío y de los animales salvajes. El gran aporte para la humanidad fue la utilización del fuego, para preparar alimentos, mantener el calor corporal y alejar animales.',
        imagen: require('@/assets/curso/15.svg'),
      },
      {
        titulo: 'Paleolítico medio',
        texto:
          'Esta segunda etapa abarcó aproximadamente desde el 250.000 a. C. hasta el 30.000 a. C. La especie humana en continua evolución alcanza la fase de hombre de Neandertal, que se caracterizó por una complexión robusta, sofisticada inteligencia, conciencia de grupo y parentesco, y capacidad para mejorar las armas que utilizaban para la caza.',
        imagen: require('@/assets/curso/16.svg'),
      },
      {
        titulo: 'Paleolítico superior',
        texto:
          'Esta tercera etapa abarcó desde 30.000 a. C. hasta el 10.000 a. C., y supone la etapa final de paleolítico. Se destaca en esta etapa el dominio del fuego, el perfeccionamiento de herramientas de caza, y se encontró la mayor cantidad de evidencias de desarrollo artístico (pinturas rupestres encontradas en las cuevas de Altamira, ubicadas en la región española de Cantabria, y pequeñas esculturas de arcilla o de hueso, que escenifican rituales de caza a través de la representación de dibujos humanos y animales). La evolución del humano alcanzó la fase de hombre de Cromañón, con una mayor capacidad para comunicarse (Uriarte, 2020).',
        imagen: require('@/assets/curso/17.svg'),
      },
      {
        titulo: 'Neolítico, nueva piedra (12.000 - 5.000 a. C.)',
        texto:
          'El periodo neolítico es el último denominado dentro de la Edad de Piedra. Este periodo presenta especial importancia, ya que el hombre tiene un gran desarrollo cultural y agrícola, doméstica algunos animales y por primera vez deja de ser nómada. Este es uno de los periodos con mayores cambios, especialmente a nivel social, ya que se empiezan a formar los primeros asentamientos y con ello a construir lo que conocemos hoy en día como las grandes sociedades. ',
        imagen: require('@/assets/curso/18.svg'),
      },
      {
        titulo: 'Neolítico, nueva piedra (12.000 - 5.000 a. C.)',
        texto:
          'El hombre aprende nuevas técnicas de siembra, cultiva arroz, maíz y trigo, lleva a cabo avances en agricultura, recoge frutos, empieza la domesticación de animales destinados a la ganadería, y adapta el medio ambiente a sus necesidades. A pesar de esto, con el crecimiento de la población, se empiezan a magnificar los problemas, se presentan las primeras guerras y se enfrentan muchos problemas de corte social. Continúa elaborando herramientas y elementos en piedra, madera y otros materiales. ',
        imagen: require('@/assets/curso/19.svg'),
      },
    ],
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

<style lang="sass">
.infografia-autores
  position: relative
  &__img
    img
      position: absolute
      transition: opacity 0.3s ease-in-out
      opacity: 0
      &:hover
        opacity: 1
</style>

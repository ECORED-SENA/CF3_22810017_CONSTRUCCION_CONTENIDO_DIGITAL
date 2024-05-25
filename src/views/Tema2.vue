<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Creación de audio
    
    .row.mb-5
      .col-lg-7.mb-2(data-aos="fade-right")
        p Los anuncios publicitarios son recursos importantes para transmitir un mensaje. Un audio original que sea fácil de entender y que cumpla la función de informar y persuadir al cliente, será una excelente táctica a utilizar. Es así como “Voy Llegando” ya inició con la estrategia de publicidad, creando una imagen como se explicó anteriormente; pero, si se le agrega un audio, podría ser aún más interesante.
        p También es importante definir el medio por el cual se va a transmitir este anuncio; puede ser netamente visual, audiovisual, sonoro, etc.
        .cajon.tarjeta--azul.p-4.mb-4.mb-lg-0
          p.mb-0 La idea es hacerlo a través de una herramienta gratuita como 
            strong Audacity. 
            | Ingresar y descargar la aplicación Audacityteam 
            a(href="https://www.audacityteam.org/" target="_blank") https://www.audacityteam.org/ 
            | presionando el botón de descarga 
            b DOWNLOAD AUDACITY 
            | y realizar la respectiva instalación.
      .col-lg-5.mb-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/imagen-tema2.svg', alt='Imagen decorativa') 


    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10.cajon.fondo-color-sistema-j
        .row.justify-content-center.align-items-center
          .col-lg-2.col-4.p-lg-3.py-4
            figure
              img(src='@/assets/curso/temas/audio-curso.svg', alt='Icono sobre grabación de audio')
          .col-lg-8.p-lg-4.px-4
            p Seleccionar la opción Grabar previamente y crear un guion, el cual se leerá teniendo en cuenta los siguientes consejos:
            ul.lista.lista-person-1.lista-ul--color.p-1.my-0
              li 
                i.fas.fa-check
                p.mb-0 Seleccionar el micrófono con el que se va a grabar.
              li 
                i.fas.fa-check
                p.mb-0 No grabar cerca de las paredes, porque pueden generar eco y la voz podría escucharse muy lejos.
              li 
                i.fas.fa-check
                p.mb-0 Utilizar micrófono (auriculares). El micrófono incorporado en el PC puede grabar bien, pero los micrófonos externos lo hacen mejor. Para este proceso se recomienda tener distanciado el micrófono.


    .row.justify-content-center(data-aos="fade-down")
      .col-lg-9
        .bloque-texto-a.fondo-color-sistema-k.p-4.p-md-5.mb-5 
            .row.m-0.align-items-center.justify-content-between
              .col-lg-8.mb-4.mb-lg-0
                .bloque-texto-a__texto.p-4.comillas
                  p.mb-3 Para este proyecto, no se requieren piezas de audio complejas, así que se usará la grabación de un guion relativamente corto.
                  .d-flex 
                    i.fas.fa-quote-left
                    p.text-center.mb-0 <b>Confiables, rápidos y seguros. Voy llegando domicilios. </b>
                    i.fas.fa-quote-right
              .col-lg-4      
                figure
                  img(src='@/assets/curso/temas/imagen2-tema2.svg', alt='Icono sobre dos personas grabando') 

   
    p.mb-4(data-aos="fade") A continuación, en el siguiente video se enseña cómo crear el audio para el guion propuesto.

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        figure.mb-5
          img(src='@/assets/curso/temas/img-video-temporal.png')

    
    h3(data-aos="fade-right") ¡Ahora es su turno!
    p(data-aos="fade") Teniendo claro el proceso para la creación de un audio, producir uno desarrollando los pasos descritos a continuación.

    PasosA.color-acento-contenido.mb-5(tipo="n")(data-aos="fade-down")
      .row.align-items-center
        .col-md-3.px-lg-5.p-5
          figure
            img(src='@/assets/curso/temas/icono-paso1-tema2.svg', alt='Icono de alistamiento')
        .col-md-9
          .h3 Crear un guion acorde al proyecto.  
        
      .row.align-items-center
        .col-md-9
          .h3 Grabar con cualquier dispositivo. 
        .col-md-3.px-lg-5.p-5
          figure
            img(src='@/assets/curso/temas/icono-paso2-tema2.svg', alt='Icono de grabación')

      .row.align-items-center
        .col-md-3.px-lg-5.p-5
          figure
            img(src='@/assets/curso/temas/icono-paso3-tema2.svg', alt='Icono de programa')
        .col-md-9
          .h3 Editar con Audacity. 
        
      .row.align-items-center
        .col-md-9
          .h3 Exportar a mp4.  
        .col-md-3.px-lg-5.p-5
          figure
            img(src='@/assets/curso/temas/icono-paso4-tema2.svg', alt='Icono de mp4')

    .row.justify-content-center
      .col-lg-10.cajon.fondo-color-sistema-j
        .p-4
          p.mb-0 Lo invitamos a compartir los resultados del proyecto en el foro técnico de la plataforma con una breve explicación del proceso y la experiencia durante el desarrollo de la actividad.

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

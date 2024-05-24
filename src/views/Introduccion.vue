<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.align-items-center.mb-5
      .col-lg-7.mb-2(data-aos="fade-right")
        p Ya tenemos claro cómo diseñar y planear cada una de las piezas que se pueden publicar en los diferentes medios digitales, 
          b ahora conoceremos cómo crearlas (imagen, audio y video).   
          br
          br
          | A medida que aprendamos cómo crear cada una de estas piezas, desarrollaremos un proyecto para la empresa de domicilios 
          b “Voy Llegando”
          | , la cual requiere piezas digitales para iniciar su promoción en las redes sociales, definiendo como objetivo de comunicación, la promoción de la marca, sus valores y sus servicios.

        .cajon.fondo-color-sistema-i.p-4
          p.mb-0 Como ya tenemos claro el objetivo de comunicación para 
            b “Voy Llegando”
            |, se crea una planeación de contenido que define las primeras piezas digitales que se deberán producir.

      .col-lg-5.mb-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/54642.svg', alt='Imagen decorativa') 


    .titulo-sexto.color-acento-contenido(data-aos="fade")
      h5 Calendario
    
    .tabla-b.color-acento-contenido.mb-5(data-aos="fade-down")
      .tabla-b__header
        h4.mb-0 CALENDARIO
      table
        thead.tabla-b__header2.text-white
          tr
            th 
              .h5.mb-0 Red social
            th 
              .h5.mb-0 Objetivo de comunicación
            th 
              .h5.mb-0 Tipo de contenido 
            th 
              .h5.mb-0 Guión 
            th 
              .h5.mb-0 Copy
            th 
              .h5.mb-0 Fecha
            th 
              .h5.mb-0 Observaciones                
        tbody
          tr
            td.red-social
              i.fab.fa-whatsapp
              i.fab.fa-instagram
              i.fab.fa-facebook
            td.text-small Informar
            td.text-small Identificador visual
            td.text-small Voy Llegando 
              br 
              | Domicilios 
              br 
              | Confiables 
              br
              | Rápidos 
              br
              | Seguros
            td.text-small - - -
            td.text-small 1 septiembre 2021
            td.text-small Logo minimalista, que se pueda adaptar a cualquier tipo de contenido.
          tr
            td.red-social
              i.fab.fa-whatsapp
              i.fab.fa-instagram
              i.fab.fa-facebook 
            td.text-small Promocionar
            td.text-small Historia
            td.text-small Servicio 24 horas +573001234567
            td.text-small - - -
            td.text-small 1 septiembre 2021
            td.text-small Historia tipo Poster.
          tr
            td.red-social 
              i.fab.fa-instagram
            td.text-small Presentar servicios
            td.text-small Post carrusel Instagram 
            td.text-small Compras
              br
              | Pagos
              br 
              | Comisiones
              br 
              | Mensajería
            td.text-small #VoyLlegando, servicio de domicilios, rápidos, confiables y seguros #24h  
            td.text-small 1 septiembre 2021
            td.text-small 4 imágenes con el texto del servicio.
          tr
            td.red-social
              i.fab.fa-whatsapp
              i.fab.fa-instagram
              i.fab.fa-facebook  
            td.text-small Presentar servicios
            td.text-small Historia
            td.text-small Compras
              br 
              | Pagos
              br
              | Comisiones
              br
              | Mensajería
              br
              | Servicio 24 horas
            td.text-small - - -
            td.text-small 1 septiembre 2021
            td.text-small Versión animada del carrusel.

    .row.justify-content-center
      .col-md-10
        .cajon.fondo-color-sistema-i.p-4
          p.mb-0 Ya el calendario está listo, así que 
            b ¡manos a la obra!
            br
            br
            | Produciremos piezas de contenido gráfico en 
            b Figma
            | , algunas piezas de audio en 
            b Audacity 
            | y, finalmente la producción audiovisual, integrando todos los elementos en 
            b CapCut.
            br
            br
            b ¡Muchos éxitos en tus prácticas! 
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>

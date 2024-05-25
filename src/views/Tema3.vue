<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Creación de video
    
    .row.mb-5.justify-content-between.align-items-center
      .col-lg-8.col-xxl-7.mb-2(data-aos="fade-right")
        p Crea un video sencillo de máximo 1 minuto, solo se deben tener en cuenta el guion y los demás consejos que se aprendieron anteriormente. Es así como en esta etapa de producción de contenido digital, se integran las piezas gráficas, audios y videos, para un resultado audiovisual que cumpla con las expectativas; todo esto realizado a partir del uso de un dispositivo móvil.
      .col-lg-4.mb-2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/temas/imagen-tema3.svg', alt='Imagen decorativa') 
    
    p.mb-5(data-aos="fade") Para iniciar, se recomienda tener todos los recursos copiados en el dispositivo móvil. Luego, consultar el siguiente video, el cual nos presentará paso a paso, la creación de un video.

    .row.justify-content-center
      .col-lg-10(data-aos="fade-down")
        figure.mb-5
          img(src='@/assets/curso/temas/img-video-temporal.png')


    h3(data-aos="fade-right") ¡Ahora es su turno!

    p.mb-5(data-aos="fade") Teniendo claro el proceso para la creación de un video, lo invitamos a producir un video de máximo un minuto y compartirlo en el foro técnico de la plataforma y si los desea con sus redes sociales, 
      span.etiqueta usando el hashtag 
        b #HabilidadesDigitalesSena.

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10.cajon.fondo-color-sistema-j
        .row.justify-content-around.align-items-center.p-4
          .col-lg-2.col-4
            figure
              img(src='@/assets/curso/temas/publicalo.svg', alt='Icono de notas')
          .col-lg-8
            h4 Recordar
            p.mb-0 Se puede crear todo lo que se pueda imaginar, lo importante es llevar siempre un orden y utilizar las herramientas correctas.

</template>

<script>
export default {
  name: 'Tema3',
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

<style lang="sass" scoped>
.etiqueta
  padding: 2px 6px 5px
  margin-right: 5px
  color: #12263f
  background-color: #80ed99
</style>

<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-12
        img(src="@/assets/curso/temas/intro/img.png", alt="")
      .col-11
        .bg-1.bx-sh1.b-r10.p-4.mt-n3
          p.mb-0 En este punto, se inicia el estudio del componente formativo #[b “conceptos básicos de redes y #[em networking]”]; tenga un primer acercamiento con los temas y conceptos que aquí se desarrollarán, explorando el video que se propone a continuación. ¡Éxitos!
    
    figure(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/AGaxodjQeSU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Conceptos básicos de redes y networking




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

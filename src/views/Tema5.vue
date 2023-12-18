<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Medios de transmisión

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-12
        img(src="@/assets/curso/temas/t5/img.png", alt="")
      .col-11
        .bg-2.bx-sh1.b-r10.p-4.mt-n3
          p.mb-0 Para que la comunicación entre un emisor y un receptor se realice se requiere de un medio que facilite la conexión entre ambos extremos, el cual es conocido como el medio de transmisión; este constituye el soporte físico a través del cual emisor y receptor pueden comunicarse en un sistema de transmisión de datos. Los medios de transmisión se pueden categorizar en dos grandes tipos que son los medios guiados y no guiados.

    p.mb-4(data-aos="fade") Los medios guiados conducen (guían) las señales a través de un camino físico dentro de los cuales podemos encontrar:

    .row.fondo-tema5.align-items-center.pb-5.pt-5.pt-lg-0.mb-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row
        
          .row.justify-content-center.mb-3(data-aos="fade-down")
            .col-lg-3.col-md-4.mb-3
              img(src="@/assets/curso/temas/t5/img2.svg", alt="")
            .col-lg-3.col-md-4.mb-3
              img(src="@/assets/curso/temas/t5/img3.svg", alt="")
            .col-lg-3.col-md-4.mb-3
              img(src="@/assets/curso/temas/t5/img4.svg", alt="")
      
          p.mb-4(data-aos="fade") Las señales que transportan cada medio son distintas, por ejemplo, en la fibra óptica los que se lleva son pulsos de luz, no eléctricos, mientras que el cobre transporta impulsos eléctricos.

          .row.justify-content-center.align-items-center
            .col-lg-5.mb-3.mb-lg-0(data-aos="fade-right") 
              img(src="@/assets/curso/temas/t5/img5.png", alt="")
            .col-lg-7(data-aos="fade-left") 
              p Los medios de transmisión no guiados son aquellos cables que transportan ondas electromagnéticas sin usar un conductor físico, sino que se radian a través del aire, por lo que están disponibles para cualquiera que tenga un dispositivo capaz de aceptarlas. Normalmente, utilizan el aire como el medio a través del cual viajan las señales en frecuencias electromagnéticas, por lo que generalmente requieren de una antena que permita transmitir y recibir datos de diferentes tipos.


    p.mb-4(data-aos="fade") Dentro de los medios de transmisión no guiados se puede encontrar:

    .row.mb-3.justify-content-center(data-aos="fade-down")
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico1.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Radiofrecuencias
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico2.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Microondas
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico3.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Infrarrojos

    .row.mb-3.justify-content-center(data-aos="fade-down")
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico4.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 #[em Bluetooth]
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico5.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Wifi
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t5/tarj-ico6.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Satelital


</template>

<script>
export default {
  name: 'Tema5',
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

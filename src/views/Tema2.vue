<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.pb-0.p-md-5.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Modelos de referencia

    p(data-aos="fade") Los modelos de referencia se basan en la definición de una serie de capas, las cuales tienen cada una sus propias funciones y características, que se encargan de resolver un problema diferente en la comunicación; cada fase tiene un orden específico y cada una se sustenta en la capa anterior.

    p(data-aos="fade") En relación con los modelos de referencia, tenga presente los siguientes aspectos:

    .row.fondo-tema2.align-items-center.py-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row

        .tarjeta.fondo-slider.p-4.mb-5(data-aos="fade-down")
          SlyderA(tipo="b")
            .row.justify-content-around.align-items-center
              .col-md-6.mb-4.mb-md-0
                h3 Propósito e intencionalidad 
                p Los modelos de referencia tienen como propósito asistir en la comprensión más clara y sencilla de las funciones y los procesos involucrados en la interconexión de los diferentes dispositivos de red.
              .col-md-3
                img(src='@/assets/curso/temas/t2/slider-img1.png', alt='')
            .row.justify-content-around.align-items-center
              .col-md-6.mb-4.mb-md-0
                h3 Forma de operación 
                p Para cumplir el propósito de los modelos de referencia, se establece una serie de capas que, más que entrar en los detalles de las especificaciones técnicas requeridas en cada una de ellas, ayudan en la comprensión de lo que sucede, contribuyendo en el logro de un mejor entendimiento de las funciones y procesos involucrados.
              .col-md-3
                img(src='@/assets/curso/temas/t2/slider-img2.png', alt='')
            .row.justify-content-around.align-items-center
              .col-md-6.mb-4.mb-md-0
                h3 Histórico de los modelos de referencia 
                p Al inicio del desarrollo de la tecnología y más propiamente de la computación, los diferentes fabricantes construían sus equipos y dispositivos para que fueran compatibles con dispositivos de sus propias marcas, lo que no facilitaba la interconexión de equipos y dispositivos de fabricantes distintos.
              .col-md-3
                img(src='@/assets/curso/temas/t2/slider-img3.png', alt='')
            .row.justify-content-around.align-items-center
              .col-md-6.mb-4.mb-md-0
                h3 Estandarización
                p La situación anterior, llevó a la necesidad de estandarizar; de esta manera se permitió la interconexión de una amplia gama de dispositivos, sin importar fabricante o tipo de #[em software]. Para que el intercambio de información sea posible se requiere el establecimiento de una serie de estándares.
              .col-md-3
                img(src='@/assets/curso/temas/t2/slider-img4.png', alt='')
    
        p.mb-4(data-aos="fade") Entre las organizaciones más destacadas, dedicadas a la construcción de tales estándares, se encuentran:

        .row.justify-content-center
          .col-lg-9
            .row
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200(@mouseover="indicadorTarjetaSlide = false")
                  .indicador--hover(v-if="indicadorTarjetaSlide")
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 #[em Internacional Standards Organization]
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-1.png')})`}")
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 Instituto Nacional Americano de Normalización
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-2.png')})`}")
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 Asociación de Industrias Telecomunicaciones
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-3.png')})`}")
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 Instituto de ingenieros electrónicos y eléctricos
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-4.png')})`}")
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 Asociación de Industrias Electrónicas
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-5.png')})`}")
              .col-lg-4.col-md-6.mb-3
                .tarjeta-slide.arriba.bt-tarjeta.bb-tarjeta.min-h200
                  .tarjeta-slide__contenedor.bg-7.h-100.align-items-center.d-flex
                    .tarjeta-slide__contenido.p-4.p-lg-5
                      h4.text-center.mb-0 Unión Internacional de Telecomunicaciones
                    .tarjeta-slide__img(:style="{'background-image': `url(${require('@/assets/curso/temas/t2/tarj-6.png')})`}")

          .col-lg-3
            .tarjeta.bg-6.p-4.h-100
              img(src="@/assets/curso/temas/t2/ico.svg", style="max-width: 100px;")
              p.text-white.mb-0 ISO definió un modelo de referencia como estándar para posibilitar las comunicaciones electrónicas a nivel global, conocido como el modelo OSI (Interconexión de Sistemas Abiertos). Para el caso de IEEE, es el organismo encargado de fijar los estándares para los elementos físicos de una red, cables, conectores e interfaces.

      

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    indicadorTarjetaSlide: true,
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

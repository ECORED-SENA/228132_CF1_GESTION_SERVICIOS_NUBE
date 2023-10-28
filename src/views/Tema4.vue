<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Puertos de comunicación

    .tarjeta.fondo-tema4.p-4.p-md-5.mb-5
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0
          img(src="@/assets/curso/temas/t4/cta.svg")

        .col-md.col-lg-6
          h4 Puertos de comunicación
          p.mb-5 Los puertos físicos permiten la conexión de diferentes componentes tanto internos como externos los que se llaman comúnmente periféricos.
          
          a.boton.color-acento-botones(:href="obtenerLink('/downloads/Puertos_de_comunicacion.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download
    
    p.mb-4(data-aos="fade") Algunos puertos de comunicación con servicios de Red son:

    .titulo-sexto.color-acento-contenido.mb-2(data-aos="fade") 
      p.mb-0 #[b Figura 3.] Puertos de comunicación para servicios de red
    .row
      .col-lg-6(data-aos="fade-right") 
        .tarjeta.bg-3.p-lg-5.p-4.h-100
          img(src="@/assets/curso/temas/t4/fig3.svg", alt="Figura que enuncia algunos de los puertos más comunes, para comunicación con servicios de red.")
      .col-lg-6(data-aos="fade-left") 
        .bg-2.p-4.h-100
          img(src="@/assets/curso/temas/t4/ico.svg", style="max-width: 105px;")
          p.mb-0 Para que se establezca una comunicación entre un origen y un destino se requiere entonces, que tanto el emisor como el receptor utilicen el mismo protocolo de comunicaciones, pero además, se requiere de un puerto de comunicación que facilite que los datos enviados desde el origen vayan por un canal exclusivo, por ejemplo, en la figura anterior, se muestra cómo el servicio web que corresponde al protocolo HTTP utiliza como interfaz o canal de comunicación el puerto 80.
      

</template>

<script>
export default {
  name: 'Tema4',
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

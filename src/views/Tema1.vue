<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.pb-0.p-md-5.pb-md-0.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Definición y generalidades de redes de datos

    .row.fondo-tema1.align-items-center.pb-5.pt-lg-0.pt-5
      .col-lg-12.col-12.px-lg-5.px-4
        .row

          .row.justify-content-center.align-items-center.mb-3
            .col-lg-7.mb-4(data-aos="fade-right") 
              p Las redes de datos son la interconexión de dos o más dispositivos conectados entre sí, a través de un medio de transmisión, con el propósito de compartir recursos e información. Una definición más formal de una red de datos o red de computadores es un conjunto de equipos (computadoras y dispositivos), conectados por medio de cables, señales, ondas o cualquier otro método de transporte de datos, para compartir información (archivos), recursos (discos, impresoras, programas, etc.) y servicios (acceso a una base de datos, internet, correo electrónico, chat, juegos, etc.). A cada una de las computadoras conectadas a la red se le denomina un nodo (Mansilla, 2015).
              .bg-4.p-4
                p.mb-0 Las redes de datos tienen por función potenciar e incrementar la productividad de las organizaciones al permitir que todos los dispositivos que se encuentran conectados puedan acceder a los recursos que se encuentran compartidos. En los últimos años la tecnología ha entrado a jugar un papel preponderante en el desarrollo y evolución de las organizaciones; cada vez está más inmersa en todos los procesos y actividades empresariales, personales y cotidianas.
            .col-lg-5.mb-4(data-aos="fade-left") 
              img(src="@/assets/curso/temas/t1/img.png", alt="")
      
          p(data-aos="fade") Las redes han permitido que los servicios y el acceso a estos recursos sea cada vez más necesario, ya que se requiere tener en todo momento trabajo en equipo, colaborativo y la integración entre los diferentes recursos tecnológicos, esto es lo que se conoce como #[em networking].

          p.mb-4(data-aos="fade") Para que las redes puedan interconectarse y trabajar en red, se requiere de una serie de componentes desde el punto de vista físico y lógico, dentro de los cuales se destacan los siguientes:

          .row.justify-content-center
            .col-lg-7(data-aos="fade-down") 
              .titulo-sexto.color-acento-contenido.mb-2
                p.mb-0 #[b Figura 1.] Componentes físicos y lógicos del trabajo en red
              img(src="@/assets/curso/temas/t1/fig1.svg", alt="Esquema gráfico que enuncia algunos componentes físicos y lógicos para el trabajo en red.")

      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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

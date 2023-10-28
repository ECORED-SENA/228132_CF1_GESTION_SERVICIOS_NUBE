<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido.mb-0
      .titulo-principal__numero
        span 6
      h1 Recursos compartidos

    .row.fondo-tema6.align-items-center.pt-5.mb-4
      .col-lg-12.col-12.px-lg-5.px-4
        .row(data-aos="fade-down")

          img(src="@/assets/curso/temas/t6/img.png", alt="")

    p.mb-4(data-aos="fade") Las redes de datos facilitan y potencian el trabajo en red entre los diferentes usuarios y dispositivos, de tal manera que se pueda acceder a dispositivos y recursos compartidos. Cuando mencionamos los recursos nos referimos a todos esos elementos tanto hardware como #[em software] que pueden ser compartidos y utilizados por los diferentes dispositivos conectados, estos recursos pueden ser desde el punto de vista #[em hardware]:
      
    .row.mb-3.justify-content-center(data-aos="fade-down")
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico1.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Impresora
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico2.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Scanner
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico3.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Almacenamiento

    p.mb-4.text-center(data-aos="fade") Desde el punto de vista lógico se puede compartir recursos como:

    .row.mb-3.justify-content-center(data-aos="fade-down")
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico4.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Archivos
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico5.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Base de datos
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico6.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Aplicaciones
      .col-lg-3.col-md-6
        .tarjeta-avatar-b.mb-3
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/t6/tarj-ico7.svg' alt='')
          .tarjeta.bg-2.b-r10.d-flex.align-items-center
            .p-4.text-center
              p.mb-0 Servicios


</template>

<script>
export default {
  name: 'Tema6',
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

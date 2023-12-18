<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Protocolos de comunicación

    p.mb-4(data-aos="fade") La comunicación, es un proceso abierto y de naturaleza diversa. Cuenta, en cualquiera de sus formas (como en la comunicación de equipos, por ejemplo), con una serie de elementos y actores que intervienen en ella; dentro de los cuales se pueden encontrar:

    .row.justify-content-center.align-items-center.mb-2
      .col-md-6.mb-4(data-aos="fade-right") 
        AcordionA(tipo="b" clase-tarjeta="tarjeta bg-5")
          .row(titulo="El emisor")
            .col-md-11
             p.mb-0 Que es el encargado del origen del mensaje (personas o dispositivos).
          .row(titulo="El destino")
            .col-md-11
             p.mb-0 Quien es el receptor del mensaje y también pueden ser personas o dispositivos.
          .row(titulo="El canal")
            .col-md-11
             p.mb-0 Es decir, aquel o aquellos medios por donde el mensaje viaja.
          .row(titulo="El código")
            .col-md-11
             p.mb-0 Cuyo lenguaje es utilizado para formar el mensaje.
          .row(titulo="El mensaje")
            .col-md-11
             p.mb-0 Es el elemento a transmitir (datos, información, cifras, contenidos, etc).
      .col-md-6.mb-4(data-aos="fade-left") 
        .titulo-sexto.color-acento-contenido.mb-2
          p.mb-0 #[b Figura 2.] Elementos de la acción comunicativa
        img(src="@/assets/curso/temas/t3/fig2.svg", alt="Gráfica que muestra los elementos básicos de la comunicación: emisor, mensaje, código, canal, receptor.")

    .tarjeta.bg-2.p-4.mb-4(data-aos="fade-down")
      .row.align-items-center.justify-content-center
        .col-lg-2.col-md-3.col-5.mb-3.mb-md-0
          img.px-lg-4(src="@/assets/curso/temas/t3/ico.svg", alt="")
        .col-lg-10.col-md-9 
          p.mb-0 Como se evidencia en la figura anterior, toda comunicación debe contar con un emisor, un mensaje a enviar y un código que permite que el mensaje viaje por un canal. Para que ambos actores puedan interactuar se requiere contar con un código o lenguaje común, el cual permite que se puedan entender; ese estándar o lenguaje común, es lo que conocemos como un protocolo de comunicaciones, el cual es un conjunto de normas que están obligadas a cumplir todos los dispositivos, #[em hardware] y #[em software] que intervienen en una comunicación de datos entre computadoras y demás dispositivos, sin estas reglas o estándares la comunicación resultaría caótica y por tanto imposible.

    p.mb-4(data-aos="fade") Dependiendo de los servicios a los cuales accedemos a través de las redes de computadores, se define el protocolo de comunicación que se deberá emplear en la interacción entre el usuario que solicita y accede al servicio, y el dispositivo que se lo entrega; en general en la transmisión y recepción de los datos podemos encontrar dos grandes familias de protocolos que se resumen en:

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-secundario.p-5.text-white
        .row.justify-content-center.mb-4
          .col-6.col-md-4
            figure
              img(src='@/assets/curso/temas/t3/tarj1.svg', alt='')
        h4.text-center Protocolos orientados a la conexión
        p Requieren un modo de comunicación de redes donde se debe establecer una conexión antes de transferir datos. Se identifica el flujo de tráfico con un identificador de conexión en lugar de utilizar explícitamente las direcciones de la fuente y el destino.
        p Se dice que un servicio de comunicación entre dos dispositivos está orientado a conexión cuando antes de iniciar la comunicación se valida el cumplimiento de ciertas variables como (disponibilidad, alcance, origen, destino, etc.) entre estos dispositivos y se negocian unas credenciales para hacer esta conexión más segura y eficiente.
      .col-md.tarjeta.color-primario.p-5
        .row.justify-content-center.mb-4
          .col-6.col-md-4
            figure
              img(src='@/assets/curso/temas/t3/tarj2.svg', alt='')
        h4.text-center Protocolos no orientados a la conexión 
        p Permite una comunicación entre dos puntos finales de una red en los que un mensaje puede ser enviado desde un punto inicial o de origen a otro punto o dispositivo de la red sin acuerdo previo. El dispositivo en un extremo de la comunicación transmite los datos al otro, sin tener que asegurarse de que el receptor esté disponible y listo para recibir los datos. El emisor simplemente envía un mensaje dirigido al receptor.

    p.mb-4(data-aos="fade") A continuación, se evidencian algunos ejemplos de los protocolos que son usados en los servicios que normalmente se utilizan en la comunicación entre las redes de datos.

    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade")
      p.mb-0 #[b Tabla 1.] #[em Suite] de protocolos según el modelo de referencia
    .tabla-a.color-secundario(data-aos="fade-down")
      table
        caption Fuente: SENA, 2021.
        thead
          tr.bg-6.text-white
            th Modelo OSI
            th #[em Suite] de protocolos TCP/IP
            th Modelo TCP/IP
        tbody.text-center.fw-bold
          tr
            td 
              h5 Capa de aplicación 
              h5 Presentación 
              h5 Sesión
            td HTTP, DNS, DHCP, FTP
            td Capa de aplicación
          tr
            td Capa de transporte
            td TCP/UDP
            td Capa de transporte
          tr
            td Red
            td IPv4, IPv6, ICMPv4, ICMPv6
            td Internet
          tr
            td 
              h5 Capa de enlace de datos 
              h5 Física
            td PPP, Frame Relay, Ethernet
            td Acceso a la red






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

<style lang="sass"></style>

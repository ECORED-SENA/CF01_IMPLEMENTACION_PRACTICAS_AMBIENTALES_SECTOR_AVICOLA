<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 4
      h1 Bioseguridad y sostenibilidad en sistemas productivos avícolas
    
    .row.mb-5.align-items-center
      .col-lg-3.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/1.png", data-aos="zoom-in")
      .col-lg-9.order-lg-1
        .bg-color-2.p-5(data-aos="fade-left")
          p La implementación de programas de bioseguridad en los procesos avícolas es fundamental para proteger la salud de las aves y garantizar la sostenibilidad de los sistemas productivos. Estos programas incluyen medidas de higiene, sanidad y control ambiental en todas las áreas de producción, con el objetivo de reducir la exposición a agentes patógenos que puedan afectar la eficiencia y seguridad de la producción.
    
    p.mb-5 Tanto en granjas de autoconsumo como en explotaciones comerciales, las medidas de bioseguridad y sostenibilidad deben ser aplicadas desde la planificación y construcción de nuevas instalaciones, así como en las unidades de producción ya existentes.

    .titulo-con-imagen.mb-5(data-aos="fade-right")
      .titulo-con-imagen__fondo
        img.titulo-con-imagen__imagen(src="@/assets/componentes/1.png")
        h3.titulo-con-imagen__texto Requisitos de bioseguridad e infraestructura
    
    p.mb-5 Según lo establece la Resolución 3651 de 2014, los requisitos para que una granja avícola de postura o levante sea considerada biosegura se detallan a continuación:

    .titulo-sexto.color-acento-contenido
      h5 Tabla 2.
      span Requisitos de bioseguridad e infraestructura
    
    .tabla-a.color-acento-contenido.pst
      table
        thead
          tr
            th.bg-color-6 Aspecto
            th.bg-color-6 Requisito específico
        tbody.bg-color-sintesis
          tr
            td Ubicación y distancias
            td
              ul.lista-ul.mb-0
                li.d-flex
                  i.lista-ul__vineta
                  | La distancia entre galpones debe ser como mínimo igual al ancho de cada galpón.
                li.d-flex
                  i.lista-ul__vineta
                  | La distancia entre un galpón y la cerca perimetral debe ser igual o superior a 50 metros.
                li.d-flex
                  i.lista-ul__vineta
                  | La distancia entre cercos perimetrales de una granja de postura o levante y una granja de material genético debe ser de mínimo 1 km.
                li.d-flex
                  i.lista-ul__vineta
                  | La distancia entre el cerco perimetral y otras granjas avícolas o porcícolas debe ser de al menos 500 metros.
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | La distancia al cerco perimetral de rellenos sanitarios o centros de procesamiento de residuos que generen riesgos debe ser de mínimo 3 km.
          tr
            td Infraestructura perimetral
            td 
              ul.lista-ul.mb-0
                li.d-flex
                  i.lista-ul__vineta
                  | El cerco perimetral debe impedir el ingreso de personas, vehículos y animales ajenos a la producción.
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Debe existir señalización correspondiente en cada área.
          tr
            td Sistemas de control sanitario
            td 
              ul.lista-ul.mb-0
                li.d-flex
                  i.lista-ul__vineta
                  | Contar con sistemas de desinfección.
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Contar con un área destinada al manejo y disposición de mortalidades, ubicada fuera de las zonas de producción.
          tr
            td Almacenamiento
            td
              ul.lista-ul.mb-0
                li.d-flex
                  i.lista-ul__vineta
                  | Disponer de bodega para almacenamiento de alimentos, que cumpla con los requerimientos técnicos establecidos.
                li.d-flex
                  i.lista-ul__vineta
                  | Área para el almacenamiento de insumos veterinarios.
                li.d-flex
                  i.lista-ul__vineta
                  | Bodega de equipos.
                li.d-flex
                  i.lista-ul__vineta
                  | Área para la disposición de residuos.
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Zona de almacenamiento, clasificación y embalaje de huevos.
          tr
            td Gestión operativa
            td
              ul.lista-ul.mb-0
                li.d-flex
                  i.lista-ul__vineta
                  | Cumplir con los procedimientos operativos estandarizados (POE).
                li.d-flex
                  i.lista-ul__vineta
                  | Contar con unidades sanitarias.
                li.d-flex
                  i.lista-ul__vineta
                  | Área para el tratamiento y almacenamiento de agua.
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Cabina de desinfección.
          tr
            td Condiciones ambientales
            td
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Todas las áreas deben contar con ventilación e iluminación natural o artificial adecuadas.
          tr
            td Control de calidad
            td 
              ul.lista-ul.mb-0
                li.d-flex.mb-0
                  i.lista-ul__vineta
                  | Disponer de un área exclusiva para productos no conformes.

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

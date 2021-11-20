<template lang="pug">
.btns
  img(src='@/assets/curso/97.svg', alt='Texto que describa la imagen')
  .btns__item(
    v-for="(boton, index) in botones"
    :style="getStyles(boton, index)"
    @mouseover="hover = index"
    @mouseleave="hover = null"
  )
    .indicador--hover(v-if="index === 0 && indicador")
    .btns__text.row.align-items-center.justify-content-end.px-3.py-4(v-if="index === hover" :style="{left:boton.left, top:boton.top}")
      .col-md-12.p-2
        h5.mb-3.font-weight-bold
          | {{ boton.titulo }}
        p.mb-0(v-html="boton.texto")
    
    

</template>

<script>
export default {
  name: 'BotonesC',
  data: () => ({
    indicador: true,
    hover: null,
    size: '15%',
    botones: [
      {
        pos_x: '41%',
        pos_y: '12%',
        left: '50%',
        top: '-100%',
        texto:
          'El mensaje para difundir debe ser lo más claro posible, un anuncio es efectivo cuando el cliente entiende lo que se quiere transmitir.',
      },
      {
        pos_x: '20%',
        pos_y: '32%',
        titulo: 'Principio de actualidad:',
        left: '0%',
        top: '-100%',
        texto:
          'Evolucionar al ritmo de la tecnología y utilizar los medios disponibles en el momento actual para garantizar la preservación de los documentos en el futuro.',
      },
      {
        pos_x: '62%',
        pos_y: '32%',
        titulo: 'Principio de equivalencia:',
        left: '130%',
        top: '-100%',
        texto:
          'Modificar, cuando sea necesario, la forma tecnológica sin alterar el valor evidencia de los documentos, como una medida para enfrentar la obsolescencia tecnológica y para garantizar el acceso a la información.',
      },
      {
        pos_x: '28%',
        pos_y: '63%',
        titulo: 'Principio de economía:',
        left: '-200%',
        top: '-100%',
        texto:
          'Aplicar procesos, procedimientos, métodos y técnicas de preservación viables, prácticas y apropiadas, para el contexto de los documentos, de tal modo que se asegure la sostenibilidad técnica y económica de la preservación digital.',
      },
      {
        pos_x: '53.8%',
        pos_y: '63%',
        titulo: 'Principio de normalización: ',
        left: '350%',
        top: '-100%',
        texto:
          'Generar lineamientos y herramientas basados en normas, estándares y buenas prácticas, como apoyo a la gestión y preservación de los documentos digitales.  ',
      },
    ],
  }),
  watch: {
    selected() {
      this.indicador = false
    },
    hover() {
      this.indicador = false
    },
  },
  methods: {
    getStyles(boton, index) {
      const image = this.hover === index ? boton.img_h : boton.img
      return {
        'background-image': `url(${image})`,
        top: boton.pos_y,
        left: boton.pos_x,
        width: this.size,
        'padding-top': this.size,
      }
    },
  },
}
</script>

<style lang="sass" scoped>
.btns
  position: relative
  &__item
    width: 80px
    position: absolute
    background-size: auto
    background-repeat: no-repeat
    cursor: pointer
    background-position: center
    transition: background-image 0.2s ease-in-out
  &__text
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1)
    text-align: center
    border-radius: 20px
    position: absolute
    left: 200%
    background-color: white
    width: 400px
    z-index: 100
    line-height: 1.2em
    transform: translate(-50%)
    .number
      position: absolute
      top: -10px
      left: 3%
      width: 91px

@media (max-width: $bp-max-md)
  .btns__text
    text-align: center
    width: 200px
    left: 50%
</style>

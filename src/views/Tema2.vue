<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Titulo_de_primer_nivel
    
    #t_2_1.titulo-segundo.color-acento-contenido
      h2 2.1 Tarjeta libro
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-3
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--city
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--city View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-3
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--ski
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--ski View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--ski(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-3
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--beach
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--beach View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--beach(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-3
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--camping
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--camping View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--camping(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
    separador
    
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-4
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--city
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--city View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-4
        .card-section
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--ski
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--ski View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--ski(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
    separador
    .row.mb-3
      .col-lg-2
        .card-section.h-100
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--city.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--city Profundizar
            .inside-page.inside-page-1
              .inside-page__container
                p.inside-page__text
                  | Esta herramienta permite analizar la variación entre el alcance planificado y el ejecutado de cada proyecto. Para el análisis de variación, se indica emplear herramientas de control, como inspecciones para garantizar que los entregables cumplan con los requisitos indicados.
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | Descargar PDF
      .col-lg-3
        .card-section.h-100
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--ski.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--ski Profundizar
            .inside-page.inside-page-1
              .inside-page__container
                p.inside-page__text
                  | Esta herramienta permite analizar la variación entre el alcance planificado y el ejecutado de cada proyecto. Para el análisis de variación, se indica emplear herramientas de control, como inspecciones para garantizar que los entregables cumplan con los requisitos indicados.
                a.boton.inside-page__btn.inside-page__btn--ski(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | Descargar PDF
      .col-lg-4
        .card-section.h-100
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--beach.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--beach Profundizar
            .inside-page.inside-page-1
              .inside-page__container
                p.inside-page__text
                  | Esta herramienta permite analizar la variación entre el alcance planificado y el ejecutado de cada proyecto. Para el análisis de variación, se indica emplear herramientas de control, como inspecciones para garantizar que los entregables cumplan con los requisitos indicados.
                a.boton.inside-page__btn.inside-page__btn--beach(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | Descargar PDF
    
    separador
    .row.mb-3
      .col-lg-2
        .card-section.h-100
          .card
            .flip-card
              .flip-card__container
                .card-front
                  .card-front__tp.card-front__tp--ski
                    img(src='@/assets/curso/temas/tarjetas/conectada_02.svg', alt='')
                    h2.card-front__heading City break
                    .card-front__text-price
                      | From £29
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--ski View me
            .inside-page
              .inside-page__container
                h3 For urban lovers
                p.inside-page__text
                  As cities never sleep, there are always something going on, no matter what time!
                a.boton.inside-page__btn.inside-page__btn--ski(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | View deals
      .col-lg-3
        .card-section.h-100
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--city.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--city Profundizar
            .inside-page.inside-page-1
              .inside-page__container
                p.inside-page__text
                  | Esta herramienta permite analizar la variación entre el alcance planificado y el ejecutado de cada proyecto. Para el análisis de variación, se indica emplear herramientas de control, como inspecciones para garantizar que los entregables cumplan con los requisitos indicados.
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | Descargar PDF
      .col-lg-4
        .card-section.h-100
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--city.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--city Profundizar
            .inside-page.inside-page-1
              .inside-page__container
                p.inside-page__text
                  | Esta herramienta permite analizar la variación entre el alcance planificado y el ejecutado de cada proyecto. Para el análisis de variación, se indica emplear herramientas de control, como inspecciones para garantizar que los entregables cumplan con los requisitos indicados.
                a.boton.inside-page__btn.inside-page__btn--city(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank" type="application/pdf")
                  | Descargar PDF
                .indicador--click(v-if="mostrarIndicador")
    
    separador
    .row.justify-content-center.align-items-center.mb-3
      .col-lg-6
        .card-section
          .card.card-1
            .flip-card.flip-card-1
              .flip-card__container
                .card-front.card-front-1
                  .card-front__tp.card-front__tp--camping.card-front__tp-1
                    img(src='@/assets/curso/temas/tarjetas/conectada_03.svg', alt='')
                    h3.card-front__heading Gestión del alcance
                  .card-front__bt
                    p.card-front__text-view.inside-page__btn--camping Profundizar
                    .indicador--click(v-if="mostrarIndicador")
            .inside-page.inside-page-1
              .inside-page__container
                .row.align-items-center
                  .col-md-6.mb-4.mb-md-0
                    h4 Modal 1
                    p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.
                
                  .col-md-6
                    figure
                      img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
                      figcaption Leyenda de la imagen
    
    separador

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    mostrarIndicador: true,
    indicadorTarjetaFlip: true,
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

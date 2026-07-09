---
layout: home
klass: home
lang-ref: home
permalink: /es/
title: Wild Moves
description: Portal de datos de seguimiento de animales
videos: ["/assets/images/eurodeer-02070010.mp4"]
imageLicense: "Ciervo rojo con un collar GPS en Trentino, Italia. Vídeo de la Fondazione Edmund Mach/Euromammals."
height: 60vh
composition:
  - type: heroVideo
  - type: stats
    inlineData:
      features:
        - title: <span data-ajax-url="https://api.gbif.org/v1/dataset/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b">~350</span>
          description: Conjuntos de datos
          href: /es/dataset/search
        - title: <span data-ajax-path="data.occurrenceSearch.cardinality.speciesKey" data-ajax-url="https://graphql.gbif.org/graphql?query=query{occurrenceSearch(predicate:{key:%22networkKey%22,type:equals,value:%22ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b%22}){_predicate%20cardinality{speciesKey}}}">~70</span>
          description: Especies
          href: /es/species
        - title: <span data-ajax-url="https://api.gbif.org/v1/occurrence/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b&limit=0">~15,000,000</span>
          description: Registros
          href: /es/occurrence/search
  - type: split
    inlineData:
      title: Búsqueda de conjuntos de datos
      description: >
        Wild Moves te ayuda a descubrir conjuntos de datos de seguimiento de animales y de bio-logging publicados en [GBIF](https://www.gbif.org/es).
        Busca metadatos para encontrar conjuntos de datos relevantes para ti.
        O sumérgete en los datos de registros que estos conjuntos de datos contienen de manera colectiva.
      cta:
        - text: Explora los metadatos
          href: /es/dataset/search
        - text: Explora los registros
          href: /es/occurrence/search
      background: /assets/images/otn-shark-tagging.jpg
      imageLicense: Marcaje de un tiburón azul en la costa atlántica de Canadá. Imaged de la Ocean Tracking Network.
  - type: split
    inlineData:
      title: Haz que tus datos sean fáciles de encontrar
      description: >
        ¿Quieres que otros descubran tus datos de seguimiento de animales y los utilicen para investigación y conservación?
        Publica tu conjunto de datos en [GBIF](https://www.gbif.org/es), regístralo en la [Red de Wild Moves](https://www.gbif.org/network/ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b)
        y aparecerá automáticamente en este sitio web.
      cta:
        - text: Conviértete en editor
          href: https://www.gbif.org/es/become-a-publisher
      background: /assets/images/lbbg-73826.jpg
      imageLicense: Gaviota sombría con un dispositivo GPS en Bélgica. Imagen de Misjel Decleer/VLIZ.
      reverse: true
  - type: floatingText
    inlineData:
      klass: hp
      title: ¿Te interesan los datos de cámaras trampa?
      description: >
        [Visita Wild Album](https://album.wildlabs.net/es/){:.button}
      hasWhiteText: true
---

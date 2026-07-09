---
layout: home
klass: home
lang-ref: home
permalink: /
title: Wild Moves
description: Animal tracking data portal
videos: ["/assets/images/eurodeer-02070010.mp4"]
imageLicense: "Red deer with a GPS collar in Trentino, Italy. Video by Fondazione Edmund Mach/Euromammals."
height: 60vh
composition:
  - type: heroVideo
  - type: stats
    inlineData:
      features:
        - title: <span data-ajax-url="https://api.gbif.org/v1/dataset/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b">~350</span>
          description: Datasets
          href: /dataset/search
        - title: <span data-ajax-path="data.occurrenceSearch.cardinality.speciesKey" data-ajax-url="https://graphql.gbif.org/graphql?query=query{occurrenceSearch(predicate:{key:%22networkKey%22,type:equals,value:%22ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b%22}){_predicate%20cardinality{speciesKey}}}">~70</span>
          description: Species
          href: /species
        - title: <span data-ajax-url="https://api.gbif.org/v1/occurrence/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b&limit=0">~15,000,000</span>
          description: Occurrences
          href: /occurrence/search
  - type: split
    inlineData:
      title: Search for data
      description: >
        Wild Moves helps you discover animal tracking and bio-logging datasets published to [GBIF](https://www.gbif.org).
        Search metadata to find datasets relevant to you.
        Or dive into the occurrence data these datasets collectively contain.
      cta:
        - text: Explore metadata
          href: /dataset/search
        - text: Explore occurrences
          href: /occurrence/search
      background: /assets/images/otn-shark-tagging.jpg
      imageLicense: Tagging a blue shark in Atlantic Canada. Image by the Ocean Tracking Network.
  - type: split
    inlineData:
      title: Make your data discoverable
      description: >
        Want others to discover your animal tracking data and use it for research and conservation?
        Publish your dataset to [GBIF](https://www.gbif.org), assign it
        to the [Wild Moves network](https://www.gbif.org/network/ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b)
        and it will automatically appear on this website.
      cta:
        - text: Become a publisher
          href: https://www.gbif.org/become-a-publisher   
      background: /assets/images/lbbg-73826.jpg
      imageLicense: Lesser black-backed gull with a GPS tag in Belgium. Image by Misjel Decleer/VLIZ.
      reverse: true
  - type: floatingText
    inlineData:
      klass: hp
      title: Interested in camera trap data?
      description: >
        [Visit Wild Album](https://album.wildlabs.net){:.button}
      hasWhiteText: true
---

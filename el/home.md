---
layout: home
klass: home
lang-ref: home
permalink: /el/
title: Wild Moves
description: Πύλη δεδομένων παρακολούθησης ζώων
videos: ["/assets/images/eurodeer-02070010.mp4"]
imageLicense: >
  Κόκκινο ελάφι με κολάρο GPS στο Τρεντίνο της Ιταλίας.
  Βίντεο: Fondazione Edmund Mach/Euromammals.
height: 60vh
composition:
  - type: heroVideo
  - type: stats
    inlineData:
      features:
        - title: <span data-ajax-url="https://api.gbif.org/v1/dataset/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b">~350</span>
          description: Σύνολα δεδομένων
          href: /el/dataset/search
        - title: <span data-ajax-path="data.occurrenceSearch.cardinality.speciesKey" data-ajax-url="https://graphql.gbif.org/graphql?query=query{occurrenceSearch(predicate:{key:%22networkKey%22,type:equals,value:%22ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b%22}){_predicate%20cardinality{speciesKey}}}">~70</span>
          description: Είδη
          href: /el/species
        - title: <span data-ajax-url="https://api.gbif.org/v1/occurrence/search?networkKey=ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b&limit=0">~15,000,000</span>
          description: Καταγραφές
          href: /el/occurrence/search
  - type: split
    inlineData:
      title: Αναζήτηση δεδομένων
      description: >
        Το Wild Moves σας βοηθά να ανακαλύψετε δεδομένα παρακολούθησης ζώων και βιοκαταγραφής που έχουν δημοσιευτεί στο [GBIF](https://www.gbif.org).

        Αναζητήστε μεταδεδομένα για να βρείτε σύνολα δεδομένων που σας ενδιαφέρουν. Ή εξερευνήστε τα δεδομένα καταγραφών που περιέχουν συλλογικά αυτά τα σύνολα δεδομένων.
      cta:
        - text: Εξερεύνηση μεταδεδομένων
          href: /el/dataset/search
        - text: Εξερεύνηση καταγραφών
          href: /el/occurrence/search
      background: /assets/images/otn-shark-tagging.jpg
      imageLicense: >
        Σήμανση ενός γαλάζιου καρχαρία στον Ατλαντικό Καναδά. Εικόνα: Ocean Tracking Network.
  - type: split
    inlineData:
      title: Κάντε τα δεδομένα σας ανακαλύψιμα
      description: >
        Θέλετε να μπορούν άλλοι να ανακαλύπτουν τα δεδομένα παρακολούθησης ζώων σας και να τα χρησιμοποιούν για έρευνα και διατήρηση; Δημοσιεύστε το σύνολο δεδομένων σας στο [GBIF](https://www.gbif.org), αντιστοιχίστε το στο [δίκτυο Wild Moves](https://www.gbif.org/network/ab013f3a-3c00-42cb-9fdb-cb5f4ba20a4b) και θα εμφανιστεί αυτόματα σε αυτόν τον ιστότοπο.
      cta:
        - text: Γίνετε εκδότης δεδομένων
          href: https://www.gbif.org/become-a-publisher
      background: /assets/images/lbbg-73826.jpg
      imageLicense: >
        Μελανόγλαρος με συσκευή γεωεντοπισμού στο Βέλγιο. Εικόνα: Misjel Decleer/VLIZ.
      reverse: true
  - type: floatingText
    inlineData:
      klass: hp
      title: Σας ενδιαφέρουν τα δεδομένα από κάμερες παρακολούθησης πανίδας;
      description: >
        [Επισκεφθείτε το Wild Album](https://album.wildlabs.net){:.button}
      hasWhiteText: true
---

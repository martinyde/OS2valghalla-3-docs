---
layout: default
title: "Revisionslog"
parent: "Administration"
tags: ['Dokument', 'Administration', 'Dokument', 'Administration', 'Dokumentsamlingen', 'Administration', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Open document', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'old-id:26']
---

##  Forklaring 

I revisionsloggen (også kaldet audit log) kan du finde information om alle aktiviteter foretaget i systemet. Det gælder både handlinger knyttet til automatiske og manuelle processer.

Formålet med loggen er primært at undersøge, om brugere har tilgået personlige data. Derfor er filteret 'Deltager' aktiveret, når man går ind på siden, så disse aktiviteter vises som udgangspunkt.

Hvis du fjerner Deltager-filteret, vil du se mange handlinger. Fx registreres det hver gang en bruger logger ind eller får vist en side (det fremgår som en anmodning til API, hvor fx "/api/administration/area/queryarealisting" betyder, at en bruger har fået vist oversigten over områder). Denne del af revisionsloggen kan være svær at navigere i.

Trin for trin

[notfound]

  1. Brug af Revisionslog 

Fra forsiden skal du:

     1. Vælge Administration i topmenuen
     2. Klikke på Revisionslog

![Administration - Revisionslog](../sites/default/files/styles/large/public/2023-11/Administration%20-%20Revisionslog.PNG%3Fitok=JmrQFeoj)

  2. Overblik 

På overbliksbilledet kan du se de handlinger, der er foretaget ud fra det opsatte filter.

Som default er filteret sat til at vise handlinger på deltagere.

     * Du kan fjerne filteremner ved at trykke på krydset ud for dem.
     * Du kan sortere listen efter dato ved at trykke på tidspunkts-kolonnen.

![Administration - Revisionslog - Overblik](../sites/default/files/styles/large/public/2023-11/Administration%20-%20Overblik.PNG%3Fitok=pUtgxOdS)

  3. Tilgå filteropsætning 

Du kan tilgå filteropsætning ved at trykke på knappen Filtrer.

![Administration - Revisionslog - Filtrer](../sites/default/files/styles/large/public/2023-11/Administration%20-%20Filtrer.PNG%3Fitok=ziCAc71M)

  4. Opsæt filter 

Du kan filtrere i to kategorier:

     * Type
     * Handling

I Type-kategorien kan du vælge følgende:

     * Deltager
     * Liste
     * Teamansvarlig
     * Arbejdsstedansvarlig
     * API
     * Andre

I Handlings-kategorien kan du vælge følgende:

     * Opret
     * Vis
     * Rediger
     * Slet
     * Slå CPR op
     * Generer
     * Eksportér
     * Anmod

Du kan vælge flere punkter fra begge kategorier og derved lave et meget præcist filter.

Når du har opsat det ønskede filter, skal du trykke Luk.

Du kan rydde filteret ved at trykke Ryd.

![Administration - Revisionslog - Filter](../sites/default/files/styles/large/public/2023-11/Administration%20-%20Filter.PNG%3Fitok=sVQtDTfb)




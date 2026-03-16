---
layout: default
title: "Valg"
parent: "Administration"
tags: ['Dokument', 'Administration', 'Dokument', 'Administration', 'Dokumentsamlingen', 'Administration', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Dokument', 'Open document', 'Dokument', 'old-id:29']
---

##  Forklaring 

Ved hjælp af et valg konfigureres de afgørende elementer i valgafviklingen:

  * Valgtypen, som afgør hvordan det valideres om deltagerne må tage en opgave
  * Hvilken periode kommunen skal have løst opgaver
  * Valgdatoen
  * Låseperiode
  * Hvilke arbejdssteder, der skal løses opgaver på
  * Kommunikationskonfiguration
  * Aktivering/deaktivering



### Vigtigt om redigering af et valg

Bemærk at man ikke kan redigere valgtype, datointerval og valgdato samt fjerne arbejdssteder på et eksisterende valg. Det skyldes stor kompleksitet i sammenhængen mellem disse elementer og fordelingen af opgaver i valget.

Hvis du har behov for at redigere disse elementer anbefaler vi, at du duplikerer det eksisterende valg og ændrer det nødvendige på den nye kopi.

Muligheder

[notfound]

  1. Administration af valg 

Fra forsiden skal du:

     1. Vælge Administration i topmenuen
     2. Klikke på Valg

Du står nu på valgoverblikket.

![Administrartion - Valg](../sites/default/files/styles/large/public/2023-11/1.PNG%3Fitok=207MD9zJ)

  2. Valgoverblikket 

På denne side har du en oversigt over alle valg i din løsning, både aktive og inaktive.

Du har også mulighed for at:

     1. Oprette nye valg
     2. Redigere eksisterende valg
     3. Redigere kommunikationskonfiguration på eksisterende valg
     4. Duplikere valg
     5. Slette valg

![Valgoverblik](../sites/default/files/styles/large/public/2023-11/2.PNG%3Fitok=S9Pflk0F)

  3. Opret valg 

Når du skal oprette et nyt valg skal du trykke på knappen opret valg

![Administration - Valg - Opret valg](../sites/default/files/styles/large/public/2023-11/3.PNG%3Fitok=mgtD-CYk)

     1. Trin 3.1: Titel og Type 

På første trin skal du opsætte de første grundlæggende indstillinger for et valg

        1. En titel på valget. F.eks. EU-parlamentsvalg 2024
        2. Vælge en valgtype
        3. Angive en låseperiode

Valgtypen afgør, hvilken validering der kan foretages af deltagerne.   
Som udgangspunkt er OS2valghalla sat op efter lovens bestemmelser, men du kan også selv ændre i valideringen under administration af [Valgtyper](valgtyper.md)

Låseperioden angiver det tidsrum før valgdatoen, hvor deltagere ikke længere selv kan afmelde sig opgaver. I det tidsrum skal de kontakte den valgansvarlige, hvilket de oplyses om.

![Administration - Valg - Titel og type](../sites/default/files/styles/large/public/2023-11/Titel%20og%20Type.png%3Fitok=agGctCbU)

     2. Trin 3.2: Datoer 

På andet trin skal du opsætte datoer.

        1. Opsætte datointerval fra første dato til sidste dato du skal bemande arbejdspladser.
        2. Vælge en valgdato.

![Administration - Valg - Dato](../sites/default/files/styles/large/public/2023-11/7.PNG%3Fitok=zJzLOPNs)

     3. Trin 3.3: Arbejdssteder 

På tredje trin skal du vælge de arbejdssteder, du skal bemande

Du opsætter, hvilke arbejdssteder der skal fremgå på listen under administration af [Arbejdssteder](arbejdssteder.md)

![Administration - Valg - Arbejdssteder](../sites/default/files/styles/large/public/2023-11/9.PNG%3Fitok=QbUC0XN6)

     4. Trin 3.4: Kommunikation 

På sidste trin skal du opsætte kommunikation for valget.

Du skal først vælge skabeloner til standardbeskeder. Disse skabeloner bruges til alt kommunikation, som ikke bliver styret af opgavespecifik opsætning.

Du kan have tre typer af skabeloner - Digital Post, E-mail eller SMS. Det er vigtigt, du har opsat de rigtige typer af skabeloner i skabelonadministrationen.

Du opsætter skabelonerne under administration af [Beskedskabeloner](../kommunikation/beskedskabeloner.md)

Når du har udfyldt de fire trin, vil det være muligt at trykke på OK, og valget bliver nu oprettet.

Bemærk at du kan redigere opsætningen af kommunikation senere.

![Administration - Valg - Kommunikation](../sites/default/files/styles/large/public/2023-11/10.PNG%3Fitok=PcG4ffc3)

  4. Aktivér og deaktivér valg 

Når et valg aktiveres, sker der to ting:

     1. Mere funktionalitet aktiveres på den eksterne hjemmeside, så deltagerne kan få adgang til opgaver og logge ind. 
        1. Funktioner til team- og arbejdsstedsansvarlige bliver også tilgængelige
     2. Der udsendes automatisk invitationer til de deltagere, som er blevet tildelt en opgave 
        1. Bemærk at der udsendes en bekræftelse i stedet for en invitation, hvis du allerede har svaret ja på vegne af en deltager

Der udsendes ikke automatiske beskeder fra et deaktiveret valg.

**OBS!** Automatiske beskeder udsendes ikke igen, hvis man deaktiverer et igangværende valg og aktiverer det igen. Systemet registrerer, at de allerede er sendt.

     1. Aktivér valg 

        1. Klik på det røde kryds ud for det valg, som du ønsker at aktivere

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-11%20kl.%2014.49.01.png%3Fitok=hPUyILFm)

     2. Deaktivér valg 

        1. Klik på det grønne flueben kryds ud for det valg, som du ønsker at deaktivere

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-11%20kl.%2014.52.39.png%3Fitok=BP0HJ75v)

  5. Skifte valg 

Du kan skifte mellem de oprettede valg. Bemærk at de fleste data i OS2valghalla gælder på tværs af valg. Det drejer sig om:

     * Grundlæggende oplysninger konfigureret under menupunktet Administration
     * Deltagere
     * Beskedskabeloner

Ved at skifte mellem valg skiftes følgende elementer:

     * Opgaver, som er tilknyttet det valgte valg
     * Potentielle modtagere af [manuelt udsendte beskeder](../kommunikation/send-besked.md)
     * Oplysninger, som kan eksporteres under menupunktet [Lister](../lister.md)

### Sådan skifter du

     1. Scroll ned i bunden af siden
     2. Klik på "Skift valg"
     3. Vælg det ønskede valg i den dialog, som vises
     4. Klik OK

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-11%20kl.%2015.32.33.png%3Fitok=SfiPx9-Q)

  6. Duplikere valg 

Du kan duplikere et tidligere valg fra valgoverblikket. Klik på kopi-ikonet ud for det valg, som du ønsker at duplikere.

Ved duplikering er det muligt at ændre på alle parametre fra det tidligere valg som fx valgperiode, valgdato og tilknyttede arbejdssteder.

Når et valg duplikeres, overføres opgavefordelingen på de tilknyttede valgsteder. Deltagernes placering på opgaverne vil dog ikke blive overført.

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-15%20kl.%2010.56.21.png%3Fitok=qQeYoBco)

     1. Duplikeret data 

### Disse oplysninger duplikeres 1:1 fra det oprindelige til det nye valg

        * Titel
        * Valgtype
        * Låseperiode
        * Arbejdssteder
        * Kommunikationskonfiguration
        * Opgavefordeling på arbejdssteder

Alle oplysninger kan redigeres under duplikationen.

### Datointervallet konverteres til antal dage

For at sikre at opgavefordelingen duplikeres korrekt, kan systemet ikke duplikere datointervallet baseret på datoer. I stedet angives hvor mange dage før og efter valget, der skal løses opgaver

### Disse oplysninger duplikeres ikke

        * Valgdato
        * Deltageres placering på opgaver - det er altså kun opgavefordelingen, der duplikeres.

![Illustration af duplikeret data](../sites/default/files/styles/large/public/2024-05/Duplikering%20af%20valg%20-%20overblik.png%3Fitok=DRTjHt2m)

  7. Slette et valg 

Du kan slette et deaktiveret valg efter behov. Sammen med valget slettes fordelingen af opgaver på de tilknyttede arbejdssteder. Desuden slettes deltagernes tilknytning til opgaver i valget, så det kan være en god idé at eksportere en liste med oplysningerne inden valget slettes.

Hvis du har behov for at gemme opgavefordelingen, kan du duplikere valget, inden du sletter det.

     1. Gå til valgoverblikket
     2. Klik på skraldespandsikonet ud for det valg, som du ønsker at slette
     3. Klik OK i den dialog som vises.

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-13%20kl.%2012.36.35.png%3Fitok=cMtS0tjX)

  8. Redigere kommunikationskonfiguration 

Det er muligt at ændre konfigurationen af, hvilke beskedskabeloner der benyttes i et valg, og om de udsendes med Digital Post, E-mail eller SMS.

     1. Gå til valgoverblikket
     2. Klik på talebobleikonet ud for det valg, som du vil ændre kommunikationskonfigurationen på
     3. I kolonnen **Standardbeskeder** opsættes de beskeder, der udsendes som standard på tværs af opgavetyper
     4. I kolonnen **Opgavespecifikke beskeder** kan du lave undtagelser til standarden 
        1. Det er fx muligt at opsætte medarbejder-rettede opgavetyper til at udsende beskeder via E-mail. Bemærk at det kræver en beskedskabelon af typen E-mail.
     5. Lav de ændringer, som du ønsker
     6. Klik på OK

![Screenshot](../sites/default/files/styles/large/public/2024-03/Skærmbillede%202024-03-20%20kl.%2011.54.01.png%3Fitok=przHuaxH)




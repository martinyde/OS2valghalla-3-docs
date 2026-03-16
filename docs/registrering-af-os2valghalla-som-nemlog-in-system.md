---
layout: default
title: "Registrering af OS2valghalla som NemLog-in system"
tags: ['Dokument', 'Implementering', 'Dokument', 'Implementering', 'old-id:42']
---

Kommunen skal registrere OS2valghalla i portalen NemLog-In Administration, så deltagere kan logge ind i den eksterne hjemmeside med MitID.

Kommunen skal i denne forbindelse forbindelse have en NSIS-vurdering af sikkerhedsniveau. OS2 har i samarbejde med Københavns Kommune udarbejdet [dette skema](https://boks.os2.eu/s/yRyLnM3sxaeAjim) med vurderingen, som I bør downloade og gemme.

Bemærk at denne registrering er nødvendig, selvom Fælleskommunal Adgangsstyring/KOMBIT Context Handler 2 er opsat.

##  Guide til oprettelse af OS2valghalla 

En medarbejder med adgang til [NemLog-In Administration](https://administration.nemlog-in.dk/) kan følge denne guide for at oprette OS2valghalla som NemLog-in system

[notfound]

  1. Log ind 

Log ind i administrationsmodulet for NemLog-in: <https://administration.nemlog-in.dk/>

  2. Opret et IT system 

     1. Klik på IT-systemudbyder
     2. Klik på Opret nyt it-system

![Screenshot af administrationsinterface](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System.png%3Fitok=Xolg4Wjn)

  3. Indtast oplysninger 

**OBS!**[kommune] er kommunenavnet, f.eks. København eller Holbæk. Det skal være formateret, så det ikke indeholder æøå, eksempelvis “koebenhavn” eller “holbaek” ligesom i URL’en til applikationen.

     * **Navn** : **[** kommune**]** -OS2valghalla-Prod
     * **Dansk beskrivelse** : OS2valghalla er et valgplanlægningssystem til opgaver omkring et valg.  
Borgere kan melde sig som frivillige og skal logge ind med MitID for at administrere egne opgaver.
     * **Engelsk beskrivelse** : OS2valghalla is an election planning system with different tasks for elections.  
Citizens can volunteer and they need to log in with MitID to administer their own tasks.
     * Vælg **Log-in tjeneste (Offentlig) – OIOSAML 3**

Når alt er udfyldt klik **Start tilslutning af it-systemet**

![Screenshot af administrationsinterface](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_2.png%3Fitok=8aMbJeKy)

  4. Vælg IT-leverandør 

På det næste skærmbillede kan der vælges en IT-leverandør i venstremenuen:

     1. Klik på **Tilføj ny it-leverandør**  
Tilknyt IT-leverandør med følgende oplysninger: 
        1. **Navn** : Foreningen OS2 - Offentligt digitaliseringsfællesskab
        2. **CVR** : 41849983
     2. Indtast CVR nummer og **Tilføj valgt IT-leverandør**

Når it-leverandøren er tilføjet kan man gå videre til det næste skridt.

![Screenshot af administrationsinterface](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_3.png%3Fitok=9UN8sxfk)

![Screenshot af administrationsinterface](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_4.png%3Fitok=Roj6Vj6E)

  5. Tilføj teknisk administrator 

     1. På it-system oversigtssiden vælges **Tilføj teknisk administrator**
     2. Der enten søges efter brugere, eller de kan oprettes manuelt 
        1. Som regel skal de oprettes manuelt
     3. Manuel oprettelse af teknisk administrator(e) med følgende oplysninger: 
        1. **Navn** : Dany Abdelke

**E-mail** : [dany.abdelke@preciofishbone.se](mailto:dany.abdelke@preciofishbone.se)

     4. RID-numre fremsendes til systemopretter på opfordring 
        1. Systemopretter sender en mail til Dany, som fremsender begge RID-numre

Klik **Tilføj** når informationerne er udfyldt.  
Gentag processen for hver teknisk administrator, der skal tilføjes.

Nu skulle det være muligt for Precio Fishbone at arbejde videre med registreringen, til den er færdig, og systemet er overført til produktion.

![Screenshot af administrationssystem](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_5.png%3Fitok=M1z357Av)

![Screenshot af administrationssystem](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_6.png%3Fitok=eqVgIqv3)

![Screenshot af administrationssystem](../sites/default/files/styles/large/public/2024-01/OS2ValghallaNemLogIn_Opret_IT_System_7.png%3Fitok=RVfG8YOO)




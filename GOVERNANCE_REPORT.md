# OS2displays's Governance Report 

Dene checkliste er baseret på [OS2s standard governance rapport](https://github.com/OS2offdig/Governance_Reports). Det er en checklist som skal tydeliggøre i hvilken grad produktet efterlever OS2s governance model.

OS2display er klassificeret som et niveau x produkt i OS2 jf. nedenstående.


**RELEVANS**

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
|  <ul><li> [x] </li> | R1 | Løsningen skaber lokal værdi | Den bidrager til skærmløsninger i flere kommuner og bruges både i interne lokaler og på offentlige områder som biblioteker, lokalcentre og offentlige pladser | 0 |
| <ul><li> [x] </li> | R2 | Løsningen skaber potentielt værdi for andre | Det er en løsning med stor fleksibiblitet og mulighed for at bruge uden licenser, hvorfor det er et billigt alternativ til andre løsninger med licenser | 1 | 
| <ul><li> [x] </li> |  R3 |Løsningen er accepteret af lokal linjeledelse | Løsningen har lokal ledelses opbakning idet at der er kommuner der har underskrevet en tilslutningserklæring og bakker op med økonomi og viden i projektet  | 2 |
| <ul><li> [x] </li> | R4 | _Løsningen har tværkommunal potentiale (anbefaling)_ | Der vil på sigt kunne deles indhold på tværs af kommuner, hvis dette ønskes | 2 |
| <ul><li> [x] </li> |  R5 |Ophæng til nationale strategier er til stede | ?| 3 |


<br>
<br>


**FORMKRAV**

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| <ul><li> [x] </li> | F1 | Kildekoden deles | https://github.com/OS2display | 0 |
| <ul><li> [x] </li> | F2 |Open Source licenskriterier overholdes | MPL 2.0 og CC-BY-SA-4.0 vedtaget | 0 |
| <ul><li> [X] </li> | F3 |Udbudsregler og alm. lovformlighed er overholdt | ? | 0 |
| <ul><li> [x] </li> | F4 |Der er tænkt på sikkerheden i løsningen | [Se dokumentationen](https://github.com/os2display/display-docs)| 0 |
| <ul><li> [x] </li> | F5 | Løsningens formål og værdi er beskrevet | ?| 0 |
| <ul><li> [x] </li> | F6 | Kildekoden er placeret på OS2's github | https://github.com/OS2display | 1 |
| <ul><li> [x] </li> | F7 | Driftskrav til løsningen er dokumenteret | [Se dokumentationen](https://github.com/os2display/display-docs)| 1 |
| <ul><li> [x] </li> | F8 | Løsningen er dokumenteret på teknisk niveau  | [Se dokumentationen](https://github.com/os2display/display-docs) | 1 | 
| <ul><li> [x] </li> | F9 | Teknisk implementering af løsningen er dokumenteret  | [Se installationsguide](https://github.com/os2display/display-docs/blob/main/installation.md)| 1 |
| <ul><li> [x] </li> | F10 | OS2's kommunikationskanaler anvendes (OS2.eu)   | https://os2.eu/produkt/os2display | 1 |
| <ul><li> [x] </li> | F11 | OS2's værktøjer benyttes (Jira)  | [OS2's Jira](https://os2web.atlassian.net/jira/software/c/projects/DISPLAY/boards/41) | 1 |
| <ul><li> [x] </li> | F12 | Der er kun en version af core koden (Master) | Ja. https://github.com/OS2display| 2 |
| <ul><li> [ ] </li> | F13 | Der er udarbejdet præsentationsmateriale af løsningen | Hvor? | 2 |
| <ul><li> [ ] </li> | F14 | Der er udarbejdet kommunikationsmateriale til strategisk niveau | Hvor? | 2 |
| <ul><li> [ ] </li> | F15 | Best practice for implementering i organisationen dokumenteres | Hvor? | 2 |
| <ul><li> [ ] </li> | F16 | Teknisk dokumentation indeholder best practice for kodestandarder i forhold til de anvendte teknologier | [Se dokumentationen](https://github.com/os2display/display-docs) | 2 |
| <ul><li> [ ] </li> | F17 | Drifts og vedligeholdelses setup er beskrevet | Hvem drifter løsningen? er der sat økonomi af til vedligholdelse? | 2 |
| <ul><li> [ ] </li> | F18 | Rammearkitekturen og standarder er fulgt og afvigelser er forklaret | Der er ikke data fra rammearkitekturen efterspurgt i løsningen. Det er valgt at afvige fra Login via rammearkitekturen, fordi standarden OIDC ikke var tilgængelig på udviklingstidspunktet og det vurderes at dette er fremtidens loginform. | 2 |
| <ul><li> [ ] </li> | F19 | _Løsningen er leveret i et containerformat fx docker (anbefaling)_ | Ja. | 2 |
| <ul><li> [ ] </li> | F20 | _Uddanelses materiale er udarbejdet (anbefaling)_ | Hvor? | 2 |
| <ul><li> [ ] </li> | F21 | Politisk kommunikation er udarbejdet (Lokal + Omverden) | Hvor? | 3 |
| <ul><li> [ ] </li> | F22 | Procesplan + procesansvar for driftsimplementering er udarbejdet ([eksempel](https://os2mo.readthedocs.io/en/development/operation/cookbook.html)) | Hvor? | 3 |  


<br>
<br>



**STRATEGISK SAMMENHÆNG**

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| <ul><li> [ ] </li> | S1 | Produktet har en kobling til [OS2's strategi](https://os2.eu/side/os2-mission-vision) | OS2display er et nemt setup, hvor det er let for nye kommuner at komme på. Der er fra starten af diskuteret arkitektur med de involverede leverandører, for at sikre at det bleve bygget stabilt og bygget på standarder. | 1 |
| <ul><li> [ ] </li> | S2 | Løsningen understøtter innovation og open source | Systemet er open source og der tænkes hele tiden i sammenhænge mellem hvad der skal ud på skærme og hvor let dette indhold skal genereres for at kunne bidrage til effektivisering. | 1 |
| <ul><li> [ ] </li> | S3 | Produktets (forventlige) kobling til [OS2's mission, vision og strategi](https://os2.eu/side/os2-mission-vision) er beskrevet | [Se dokumentationen](https://github.com/os2display/display-docs) | 2 |
| <ul><li> [ ] </li> | S4 | Der er udarbejdet en vision og strategi for produktet | [Se dokumentationen](https://github.com/os2display/display-docs) | 2 |
| <ul><li> [ ] </li> | S5 | Produktets kobling til og overensstemmelse med OS2's vision og strategi er tilstede og beskrevet | [Se dokumentationen](https://github.com/os2display/display-docs) | 3 |



<br>
<br>

  
    

**GOVERNANCE**

|     |  #  | Krav | Henvisning | Niveau | 
| --- | --- | --- | --- | --- |
| <ul><li> [ ] </li> | G1 | Produktet er oprettet i OS2's porteføljestyring (Hjemmeside) | https://os2.eu/produkt/os2display | 1 |
| <ul><li> [ ] </li> | G2 | Der koordineres løbende med OS2-sekretariatet  | Koordinationsgruppen bruger aktivt sekretariatet til indkaldelse af møder mv. | 1 |
| <ul><li> [ ] </li> | G3 | Der er udpeget en projektleder/tovholder | Hvem? evt. link til beskrivelse af ansvar/opgaver | 1 |
| <ul><li> [ ] </li> | G4 | Bestyrelsen er orienteret | fx link til referat | 1 |
| <ul><li> [ ] </li> | G5 | Bestyrelsen har godkendt produktet | fx link til referat | 2 |
| <ul><li> [ ] </li> | G6 | Der er nedsat en styregruppe | Link til kommissorium | 2 |
| <ul><li> [ ] </li> | G7 | _Der er nedsat en koordinationsgruppe (anbefaling)_ | Link til kommissorium | 2 |
| <ul><li> [ ] </li> | G8 | _En projektmodel anvendes og er dokumenteret (anbefaling)_ | Hvor? | 2 |
| <ul><li> [ ] </li> | G9 | _Review af kode foretages af tredjepart (anbefaling)_ |  | 2 |
| <ul><li> [ ] </li> | G10 | _Der er udarbejdet en tilslutningserklæring til sikring af økonomi (anbefaling)_ | Hvor? | 2 |
| <ul><li> [ ] </li> | G11 | Bestyrelsen har godkendt styregruppen | fx link til referat | 3 |
| <ul><li> [ ] </li> | G12 | Bestyrelsen er repræsenteret i styregruppen | fx link til referat | 3 |
| <ul><li> [ ] </li> | G13 | Der foreligger en aftale der sikre økonomi til koordinerg og videreudvikling | Link til aftale | 3 |
| <ul><li> [ ] </li> | G14 | Der er etableret et fagligt fælleskab bag løsningen hvor erfaringer kan udveksles | Henvisning til en faggruppe eller et forum | 3 |
    

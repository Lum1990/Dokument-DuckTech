# DuckTech - Data Migrering

v. 0.1.2 Datum: 04/05/2026 Författare: Mikael

<details>
 <summary>Dokuments ändringar </summary>

|**Version**|**Datum**|**Ändring**|**Författare**|
|:---|:---|:---|:---|
|0.1.2| 04/05/2026|Uppdaterat dokumentation, börjat med riskanalys|Mikael|
|0.1.1| 30/04/2026|La till dokument version|Mikael|
|0.1.0| 30/04/2026|Dokument skapat|Mikael|

</details>


## Innehållsförteckning
**1.** Bakgrund till migrering<br>
**2.** Säker dokumentation och ITIL
**3.** Roller och ansvarsområden<br>
**4.** Projektmodell: Hybrid (Vattenfall + Scrum)<br>
**5.** Anpassning och utbildning<br>
**6.** Riskanalys<br>



## Om DuckTech
DuckTech förser företag med modern och säker Cyber- och IT-infrastruktur. Försvarsmakten har länge varit DuckTech´s största kund men har under de senaste årens poltiska 
utveckling ökat sina krav på säkerhet och suviränitet. För att fortsatt få leverera till försvarsmakten måste DuckTech anpassa sin verksamhet efter dessa krav.

Anställda ca: 100

### 1. Bakgrund till migrering.
DuckTech´s nuvarande molntjänst hos Google Workspace ses inte längre som ett säkert alternativ. Försvarsmakten
har höjt sina krav på säkerhet och suviränitet, för att uppfuylla detta har DuckTech valt att skapa sin egen molntjänst och migrera sin data från Google Workspace till
privat server, försvarmakten baserar sin analys pga av det politiska läget i USA och omvärlden.

Huvudsyftet men migrationen är att skapa en säker och isolerad miljö för vidareutveckling av Cyber- och IT-infrastruktur för militärt bruk. 
Under detta projekt kommer omfattande riskanalys genomföras av lokaler, personal, hård och mjukvara för att säkerställa kraven från FMV.

### 2. Säker dokumentation och ITIL
Djupgående dokumentation kommer ske löpande under projektets gång och efter att projektet är avklarat, uppdatering av dokumentationen när verksamheten utvecklas 
kommer också vara av stor vikt. Förvaring av dokument ska säkerställas så obehöriga ej får tillgång till dokumentationen, krav: SUA (Säkerhetsskyddad upphandling).
Server konfigurering kommer dokumenteras av samtliga servrar och backup kommer göras. Nya rutiner för dokumentation kommer krävas av de anställda då det är mycket viktigt
om ändringar sker.

ITIL kommer tillämpas för att DuckTech på ett effektivt och skalbart sätt ska kunna utveckla sin verksamhet efter behov. 
Stor fokus kommer läggas på Change Management eftersom stora förändringar inom företaget kommer ske med eget ansvar för tex. backups, underhåll av serverhallar och övrig 
IT-infrastruktur. 

### 3. Roller och ansvarsområden
|Roll|Namn|Ansvar |
|:---|:---|:---|
|**Kravansvarig**| Ahmed| Regelbunden kontakt med FMV för att säkerställa att krav uppfylls och meddela projektledningen om ändringar sker. |
|**Presentation**| Jonas| Tillhandahåller information om förändringar i DuckTechs verksamhet till de anställda och utbildar personalen gällande nya rutiner och verktyg. |
|**Teknikansvarig**| Patrik|Ansvarar för att lokaler och hårdvara uppfyller säkerhetskraven. Överser byggnationen av serverhallar. |
|**Dokumentation**| Mikael|Utför dokumentation av arbetet. |
|**Testare**| Abdinasir |Testning av system och hårdvara. |

### 4. Projektmodell: Hybrid (Vattenfall + Scrum)
Då projektet har en längre tidsram, >1år, kommer planeringen använda en hybridmodell, vattenfallsmodellen och Scrum. Projektet kommer delas upp i mindre projekt månadsvis, 
med undantag av säkerhetsprövning av personalen. Vattenfallsmodellen fungerar bra för att få en överblick av projektet i sin helhet, mindre projekt kommer 
följa den övergripande planeringen. Det är viktigt att varje delmoment följer “vattenfallets” helhet då överliggande projekt är kritiska för att underliggande projekt 
ska kunna starta.  

Scrum kommer tillämpas för varje delmoment för att eventuella förändringar ska kunna hanteras snabbt och flexibelt för att leva upp till den övergripande tidsplanen. 

### 5. Anpassning och utbildning
Säkerhetsprövning kommer ske löpande under projektets 4 första månader. Om någon av de anställda brister i säkerhetskonrtollen får DuckTech starta
rekrytering av ny ansställd för att täcka den tappade rollen. Nya säkerhetskrav kommer ställas på de anställda och utbildning kommer ske under projektets gång för att 
säkerställa att kraven på personal uppfylls.
Även utbildning inom de nya systemen kommer ske löpande när projektet börjar närma sig slutfasen.
Eventuell rekrytering kommer ske för att täcka underhåll av serverhallar och för hantering av incidenter, tex driftstop av server eller dataintrång.
ITIL kommer vara centralt för förändringarna och fortsatt verkasmhet. Change, problem och incident management kommer ha stort fokus när
företager går från publikmolntjänst till lokal. 
#### 5.1 Change
Det kommer vara en stor omställning för DuckTech, för att få en bra övergång till det nya arbettsättet kommer personalen löpande utbildas 
och nya rutiner kommer implementeras. Behörigheter måste bestämmas, vem som har behörighet till vad.
#### 5.2 Problem
Vid en stor omställning är det nästan omöjligt att undvika problem, det är viktigt att uppdaga problem i ett tidigt skede eller omstäntigheter som kan leda
till framtida problem. Här kommer noggrann dokumentation vara viktigt för att kunna se var problemet har sitt ursprng och vad man kan göra för att undvika det
i framtiden.
#### 5.3 Incident
Sätta upp en tydlig plan vid driftstop eller dataintrång. Vem ansvarar för drift av servrar? Vem hanterar eventuella dataintrång.
Hur hanteras gammal hårdvara?

### 6. Riskanalys
Djupgående analys om lokaler, personal, hård och mjukvara. Lokaler för serverhallar och arbetsutrymmen kommer anpassas efter FMV´s krav på säkerhet.
Handlingsplan för eventuella dataintrång och driftstop av servrar. Stort fokus kommer läggas på redundans och high availability. 

### Risk: Planering och byggnation
|Risk|Beskrivning|Sannolikhet|Konsekvens|Risknivå|Åtgärd|
|:---|:---|:---|:---|:---|:---|
|**Säkerhetsprövning**|Nyckelpersonal nekas säkerhetsklassning|2|4|8|Ha konsulter reda för att täcka behovet tills ny medarbetare kan anställas.|
|**Hårdvara**|Brist på hårdvara pga värdsläget och stora inköp till AI-datacenter|4|4|16|Planera inköp i ett tidigt skede.|
|**Spräckt budget**|Nya krav från FMV|2|3|6|Change management och tydlig kommunikation med DuchTech om krav ändras.|
|**Serverhallar**|Förseningar och dolda fel|3|3|9|Noggrann inventering av lokaler och tidsbuffert.|

### Risk: Nätverk och grundinstallation
|Risk|Beskrivning|Sannolikhet|Konsekvens|Risknivå|Åtgärd|
|:---|:---|:---|:---|:---|:---|
|**Kablage**|Bristande kvalite|1|4|4|Noggrann upphandling och kvalitets kontroll.|
|**Personalbrist**|Frånvaro pga sjukdom, ledighet eller liknande|2|3|6|Planering och säkerhetsklassad extrapersonal som kan rycka in vid behov.|
|**Spräckt budget**|Nya krav från FMV|2|3|6|Change management och tydlig kommunikation med DuchTech om krav ändras.|

### Risk: Migration
|Risk|Beskrivning|Sannolikhet|Konsekvens|Risknivå|Åtgärd|
|:---|:---|:---|:---|:---|:---|
|**Dataläcka**|Data exponeras mot internet under migration|2|5|10|Använd VPN vid export.|
|**Big Bang-haveri**|De nya servrarna orkar inte med lasten vid driftsättning|1|5|5|Genomför migrering stegvis och ha roll back planerat.|
|**Korrupt data**|Data korrumperas under export|2|5|10|Använd haschar för att kontrollera data förre och efter flytt.|

### 7. Planering och kommunikaiton






## Group Reflection - Week 6

### The chosen scope of the application 
*(under development including priority of features and for whom you are creating value)*

Under sprint nummer 5 färdigställdes i stort vyn ETA-view. Vyn skall skapa värde för kaptenen genom att underlätta rapporteringen. Ambitionen var att vyn skulle visa de rapporterade ETA:er som berörde fartyget, samt att nya ETA:er skulle kunna skickas. Vyn sorterar nu ut de states som berör Estimated Time of Arrival till Vessel Traffic Area. Det som återstår för att färdigställa funktionen i vyn är att koppla det redan skapta rapporteringsformuläret till knappen för att skicka ett ETA. Gruppen hade önskat att bli klara med detta under sprinten, men på grund av osäkerheter i vyns utformning drog ut på tiden. Detta kan undvikas genom att tidigare under processen bestämma design och utformning innan utvecklingen påbörjas. Då minskar kraven på att andra komponenter skall färdigställas innan nästa kan påbörjas. 

### The success criteria for the team
*(in terms of what you want to achieve with your application)*

Tre KPI:er används för att mäta gruppens prestation. Vi har fortsatt med de tidigare KPI:er. 
Happiness:1 . Arbetsbördan har känts bra under veckan och alla mår bra. Arbetet har flutit på och fokuset har legat på utveckligen av ETA-viewen. Vissa tasks estimerades med lite för lite tid, vilket gjorde att vissa delar av arbetet inte hann färdigställas. Ytterligare något som skapade stress bland gruppdeltagarna var att utvecklingsmiljöerna åter krånglade, vilket gjorde att arbetet inte kunde fortsätta som planerat. De berörda deltagarna arbetade då istället med review och planering av slutrapporten, och kunde på så sätt bidra till gruppens arbete under sprinten. 

Doneness: 1. Vi har under sprinten lämnat ett fåtal av tasksen i “in progress” då de inte blev färdigställda. Detta för att vi återigen underskattade tiden för några enstaka tasks. Den interna kommunikationen var någorlunda bristfällig kring en del av designen vilket resulterade iatt tid lades på att reda ut oklarheterna. 
Scrumness: 0. Vi har följt vår scrum-guide under sprinten. Daily scrums har genomförts de dagar som vi arbetat, och review har genomförts efter sprintens slut. Dessutom genomfördes en kortare retrospective med end-user som fick utvärdera den adderade funktionaliteten. Scrum of scrums har genomförts med delar av de andra scrum-mästarna och inget särskilt uppkom därifrån. Alla i gruppen deltar aktivt i scrum-arbetet. Gruppen önskar inte att förändra arbetet med Scrum utan bedömer att det nuvarande arbetssättet fungerar väl. 


### Your acceptance tests
*(such as how they were performed and with whom)*

Acceptanstest för denna sprint var liksom förra veckan att kunna kompilera appen med de tillägg som gjorts. Då vissa av featuresen inte är färdigställda har dessa inte kunnat testas. Målet med att kunna uppvisa en i stort sett fungerande ETA-skärm har uppnåtts, och appen går att kompilera och köra. Förhoppningen är att kunna fortsätta denna utvecklingen under nästa sprint, och uppvisa en färdigställd version av ETA-skärmen till nästa review samt att ha påbörjat en “loggbok”-view. Genom att fortsätta att ha en bra diskussion och hjälpa varandra med utvecklingen kommer gruppen att uppnå målen under nästa sprint. För varje task har individuella acceptanskriterier satts, men vikten av att featuren är kompatibel med appen är av stor vikt för utvecklingsarbetet. 

### The design of your application 
*(choice of APIs, architecture patterns etc)*
 
Vi försöker fortsatt att i största möjliga mån använda den kodstil som redan finns i appen och återanvända de delar vi kan. På så sätt blir både koden och appens utseende enhetligt och lättare att följa. Dessutom underlättar det och skyndar på processen av att skapa nytt innehåll. Genom att utforska koden noggrant och identifiera delar som går att återanvända kommer gruppen att behålla den enhetliga kodstil. 

### The behavioural overview of your application
*(for instance through use cases, interaction diagrams or similar)*

Vi har fortsatt använda scenariot som grund för hur appen ska fungera och bete sig. Därtill har vi lyssnat till product owner och end user för att förstå hur appen ska användas och hur det påverkar sättet den bör utformas på. Genom denna kontakt kommer gruppen vara säker på att appen stödjer de behov som önskas. Under kommande sprint kommer kommunikationen med end user att utökas för att få en större mängd input att arbeta med. I dagsläget finns vissa oklarheter kring vilken funktionalitet som efterfrågas. Kontakten kommer ske via mail, och skärmdumpar kommer illustrera gruppens frågor. 


### The structural overview of your application
*(such as class diagrams, domain models or component diagrams)* 

Under sprinten har skisser följts för utformandet vilket har fungerat bra och gruppen har fått en tydlig bild över vad som behöver göras. 
Nästa sprint ska en ny logg-vy skapas vilket gör att vi behöver strukturera upp vilka komponenter och funktioner som skall ingå. Logg-vyn är tänkt att visa alla rapporterade “actual” tidsstämplar för att ge underlag till kaptenen att fylla i sin loggbok. 
Ett UML diagram över ETA-vyn återfinns som bild i mappen för denna veckas reflektion. 

### Your user stories
*(in terms of using a standard pattern, acceptance criteria, task breakdown and effort estimation*)

Sprintens user stories:
Som Kapten vill jag kunna se ETAs vid varje tidsintervall, för att få en överblick över legget. 
Acceptanskriteria: En vy där ETAs delas upp i olika tidsintervall (72, 48, 24.. )

Tasks med tidsestimat i timmar: 
K7 - Timeline-vy för ETA-skärm (8+12)
K8 - Lägga till tidsval i ETA-view(6)
K11 -  Lägga till tim-formulär för ETA-skärm (6)
Som ett fartyg behöver jag meddela agenten om en ETA, för att agenten skall kunna förbereda ankomsten så bra som möjligt.
Acceptanskriteria: En vy där kaptenen kan fylla i ETA vid varje givet tidsintervall. 
Tasks med tidsestimat i timmar: 
K7 - Timeline-vy för ETA-skärm (8+12) 
Task K7 är påbörjades föregående sprint men färdigställdes ej och har således fått ett nytt tidsestimat som följts denna sprint. 


### The three KPIs you use for monitoring your progress

Vi har valt att fortsätta med tidigare valda KPIs. Doneness: bli färdiga med “User Stories” i sprint backloggen. 
Motivering: Ligga i fas, inte hamna efter. 
Allting klart: 0 
0-10%: 1 
20%+: 2 


Happiness: Alla i gruppen nöjda med arbetstempo och belastning varje gång vi träffas 
Motivering: Bra stämning i gruppen, bättre resultat. 
0: Alla mår bra 
1: Mår sådär 
2: Stressigt 

Scrumness: Hur väl vi har arbetat efter scrummetodiken. Dvs. har vi gjort; daily scrums, reviews, retrospective, scrumboard, estimates, scrum of scrums och kommunicerat med product owner och end user. Vi har satt upp en scrumguide i repot som ska följas. 
Motivering: Underlättar ett bra arbetssätt och ger oss möjlighet att utvärdera hur vi arbetar. 
0: Följt scrumboard och scrummetodiken enligt scrumguide 
1: Finns tydliga förbättringsmöjligheter 
2: Icke-fungerande


### Code quality using a tool such as Findbugs
*(1 point if your code includes issues concerning correctness or bad style, 2 points if you have dodgy or performance issues and 3 points if the code is fine),
  only asses the code you have written yourself*

Vi har under sprinten bekantat oss med Codacy och använt verktyget för att kontrollera olika grenar i repot. Då vi under sprinten främst arbetat med ETA-vyn bifogas en printscreen över den utvärdering Codacy genererat för grenen (Ligger i mappen för denna veckas reflektion). Kontroll har gjorts av kodens säkerhet, kodstilen, kompabiliteten, prestation och andelen oanvänd kod. Verktyget är användbart för felsökning och för att säkerställa att koden håller god kvalité. 
Under utvecklingen har en del buggar dykt upp vilket har hanterats under sprintens gång. De större buggar som identifierats har gjorts till egna tasks. 

### The roles you have used within the team

Tove har haft rollen som scrummaster och deltagit i scrum of scrums. Fredrik har varit kontaktperson gentemot end user. Linus och Johan har varit rumsbokare. Fredrik kommer fortsätta som kontaktperson, Tove kommer agera scrummaster och Linus kommer fortsätta boka rum.

### The agile practices you have used for the current sprint

Vi har haft daily scrums och agerat utefter vår sprint backlog. Sprinten har avslutats med en review. Arbetet har fördelats genom scrumboarden, där estimat och beskrivning av uppgiften har funnits.

### The time you have spent on the course
*(so keep track of your hours so you can describe the current situation)*

Det har varit en hel sprint denna veckan och gruppen har suttit ihop under 12h (4 handledning och 8 arbete).

### The sprint review
*(either in terms of outcome of the current week's exercise or meeting the product owner)*

Den gångna veckan har bestått av en full sprint där vi hunnit med mycket jämfört med tidigare veckor. Det börjar dra ihop sig för gruppens kandidatprojekt, vilket speglat tiden spenderat på detta projektet. Detta har resulterat i att prioriteringen i backlog:en har anpassats för att så mycket arbete som möjligt skall hinnas utföras. Vidare fick vi bra återkoppling på föregående veckas arbete, som vi därefter implementerat till en stor del. Efter samtal med end user och produktägare har gruppen fått en klar bild om vad som ska implementeras till nästa vecka.

### Best practices for using new tools and technologies
*(IDEs, version control, scrum boards etc.)*

Rasmus har genom omfattande studier på youtube lärt sig hantera Codacy. Kunskapen han nu besitter har han förmedlat till gruppen, och gemensamt har man bedömt kodkvalitén. 

### Relation to literature and guest lectures
*(how do your reflections relate to what others have to say?)*
Vi har varken haft gästföreläsning eller vanlig föreläsning med ny kurslitteratur.


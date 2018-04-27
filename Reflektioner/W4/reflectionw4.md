## Group Reflection - Week 4

### The chosen scope of the application 
*(under development including priority of features and for whom you are creating value)*

Gruppen har under sprinten identifierat de states som ansågs nödvändiga och satt dessa som default favoriter i appen. Utöver detta har ordningen i sidomenyn prioriterats om. Möjligheten finns nu även att välja endast det egna fartyget i port call view. Create port call togs bort då den inte ansågs behövas. Detta då rederiet normalt skapar port calls som sedan uppdateras av vessel. Vid kommunikation med vår end user framkom dock att denna funktionalitet kan behövas i undantagsfall, varför vi kommer att ta tillbaka den i appen i nästa sprint. För kommande sprint kommer en ny sida för att enklare hantera ETAer enligt de olika kraven på tidrapportering. Gruppen skall även utreda om det går att skapa notiser för kaptenen när en tidsrapportering närmar sig. Andra grupper skall kontaktas kring informationsutbyte med andra aktörer och hur det ska hanteras. 
Genom att dela upp arbetet i ett antal estimerade tasks som berör olika områden hoppas gruppen på att kunna leverera en ny ETA-view i slutet av sprinten. Arbetet delas upp på skelett, vyer/utseende och modal med formulär för att kunna parallellisera delar av arbetet. 

### The success criteria for the team
*(in terms of what you want to achieve with your application)*

Två av KPI:erna från tidigare sprintar har återanvänts även denna vecka. KPI:et som var tänkt att mäta kodkvalité utifrån koddoktrinen har däremot omvärderats. Vid projektets start trodde vi att vi skulle skriva betydligt mer kod på egen hand, när vi nu istället arbetar och omarbetar befintlig kod känns det valda KPI:et inte lika relevant. 
Happiness: 0. Arbetsbördan har känts bra under veckan och alla mår bra. Arbetet har flutit på och fokuset har kunnat inriktas på arbetet med apputveckling. Vi känner att vi gör framsteg och har fått bra respons från end user. 
Doneness: 1. Vi har under sprinten tömt sprint backloggen på 8/9 tasks varav den sista ligger och väntar på att bli granskad. Vi känner att vi ligger i fas och är nöjda över vår leverans denna vecka. 
Scrumness: 1. Vi har följt vår scrum-guide under veckan, men daily scrum-mötet blev under ett av tillfällena lite kort och ofokuserat. Estimaten under sprinten har varit sådär, finns rum för förbättring under nästa vecka.

### Your acceptance tests
*(such as how they were performed and with whom)*

Denna sprint ville vi kunna kompilera en avskalad version av portableCDM appen, vilket vi uppnått. Onödig funktionalitet och information har tagits bort för vara bättre anpassad till just fartyget och appen går att kompilera utan problem. I slutet av nästa sprint vill vi kunna visa upp ett fungerande första utkast av ETA-skärmen. 

### The design of your application 
*(choice of APIs, architecture patterns etc)*

Vi fortsätter använda API:er från föregående sprint utan att avvika från befintlig designarkitektur.

### The behavioural overview of your application
*(for instance through use cases, interaction diagrams or similar)*

Genom att grundligt läsa igenom det scenario som beskrivs på kurssidan har olika behov identifierats. Dels gällande information som behöver delas och som behöver tas emot, samt funktioner som kan vara önskvärda. Man har nu en mer avskalad version av appen genom att koda efter dessa user cases. 

### The structural overview of your application
*(such as class diagrams, domain models or component diagrams)*

Vi utgick från bilden som bifogades i förra veckan vid ändringar i applikationen under sprinten. Då förändringarna till största delen bestod i att skala ner funktioner gjordes inga förändringar i appens befintliga struktur.  För att underlätta utformningen av ETA-vy som skall skapas den här veckan har gruppen även skissat på hur denna ska se ut. Denna skiss kommer sedan att vara ett stöd i att utforma ETA-funktionerna.

### Your user stories
*(in terms of using a standard pattern, acceptance criteria, task breakdown and effort estimation*)

Sprintens user stories:
Som kapten vill jag bara se information som rör mitt eget fartyg. Acceptanskriteria: Ge kaptenen skärm för enbart sitt fartygs port calls.
Som kapten har jag inte ett behov av att skapa Port Calls. Acceptanskriteria: Ta bort sidan create Port Calls.
Som kapten vill jag att mina mest användbara states nära till hands. Acceptanskriteria: Lägga dessa som default favoriter. 

### The three KPIs you use for monitoring your progress

Vi har valt att fortsätta med tidigare valda KPIs med förändring av det sista. Kodkvalitén har bytts ut mot att istället utvärdera hur väl vi arbetar med scrum: Doneness: bli färdiga med “User Stories” i sprint backloggen. Motivering: Ligga i fas, inte hamna efter.
Allting klart: 0
0-10%: 1
20%+: 2
Happiness: Alla i gruppen nöjda med arbetstempo och belastning varje gång vi träffas Motivering: Bra stämning i gruppen, bättre resultat.
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

Förra veckan hann vi inte undersöka verktyg för hantering av buggar, men då det är viktigt för projektet satsar vi istället på att göra det denna vecka. 

### The roles you have used within the team

Tove har haft rollen som scrummaster och deltagit i scrum of scrums. Fredrik har varit kontaktperson gentemot end user. Linus har vart rumsbokare. Fredrik kommer fortsätta som kontaktperson,Tove kommer agera scrummaster och Linus kommer fortsätta boka rum.

### The agile practices you have used for the current sprint

Vi har haft daily scrums och agerat utefter vår sprint backlog. Sprinten har avslutats med en review. Arbetet har fördelats genom scrumboarden, där estimat och beskrivning av uppgiften har funnits. Genom kontakt med end user har en form av retrospective genomförts, som visat på vissa förändringsbehov. 

### The time you have spent on the course
*(so keep track of your hours so you can describe the current situation)*

2 timmar handledning, 4 timmar möte och sedan 8 timmar grupparbete. =>14h.

### The sprint review
*(either in terms of outcome of the current week's exercise or meeting the product owner)*

När vi denna vecka träffade end user framkom att bilden vi skapat oss förra veckan angående appens utformning inte riktigt stämde överens med hans önskemål. Vi kommer därför att omarbeta upplägget lite för att bättre passa end user för att generera så mycket värde som möjligt. Fortsatt har vi också insett vikten av att kontinuerligt kommunicera med end user/product owner för att undvika onödiga missförstånd och felaktigheter.  

### Best practices for using new tools and technologies
*(IDEs, version control, scrum boards etc.)*

Vi har blivit introducerade till react native och javascript samt använt oss av git på ett bredare och mer avancerat sätt. Gruppen har utvecklat i branches som sedan har mergeats vilket varit nytt för denna sprint. För att standardisera användandet av scrumboarden har en guide satts samman som förenklar användandet. 

### Relation to literature and guest lectures
*(how do your reflections relate to what others have to say?)*

Vi har varken haft gästföreläsning eller vanlig föreläsning med ny kurslitteratur. 



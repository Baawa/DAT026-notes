#Lecture 2

##Model selection
- Måste ske manuellt.

##Parameter estimation
- Om man har en model, kan man troligtvis välja parametrarna mha en algoritm, men man kan även välja de manuellt.

##Model
- Kan hjälpa oss att förstå problemet. T.ex. genom att ta ut derivatan på en exponentiell ekvation och på det sättet förstå varför och hur värdet växer.
- Kan även hjälpa oss med att lösa ett/flera problem, t.ex. förutsäga framtiden för en population(hur stor den kommer att vara).

##Hur man finner en model baserat på data
- Om det är något som utvecklar sig över tiden, bör man kolla på ändringen mellan punkterna. Och då kan man se om ändringen växer proportionerligt mot värdena.
  - Vi kan då ta ut deltat av värdena och få fram värdenas funktions derivata. Från derivatan kan vi sedan härleda en funktion.

Modell, en viss modell är samma sak som en instans av en modell. T.ex. Modell för en population.
Modelltyp är en gruppering av modeller som ser matematiskt "likadana" ut, t.ex. exponential funktioner.
- Det finns många olika modelltyper med olika fördelar och nackdelar, det är viktigt att välja rätt.

När man väljer modelltyp ska man fråga sig följande:
- Vad kan en modelltyp beskriva?
- Vad kan du göra med modelltypen?
Ibland kan dessa frågor vara i konflikt med varandra. Det är inte alltid viktigt med en kraftig modell utan kan vara viktigare att den är en kompromiss mellan de två frågorna.

Det är modellen som står i fokus inte lösningen eller värdet den ger.

Det finns standard "application models" som man kan använda på vissa typer av problem, t.ex. Vehicle routing problem.
(VRP - Man har en lastbilscentral och en lastbil som ska leverera varor till vittspridda punkter. Varje lastbil har en viss kapacitet, räckvidd, osv. Man vill göra rutter som maximerar varje lastbils kapacitet och täcker så många punkter som möjligt. Inte helt självklart hur de olika rutterna ska se ut.) Man kan då använda modeller för t.ex. VRP för att lösa liknande problem.

Ibland är det inte alltid tydligt om det är en modell eller en matematisk beskrivning. En matematisk beskrivning kan t.ex. vara "kortaste vägen problemet" ("Shortest path problem").

Linjära funktioner går att definiera med en ekvation, man kan ta fram förväntade svar.
Icke-linjära funktioner, kan vara t.ex. en rekursiv ekvation, kan ge oförväntade svar och "kaos", mao ett komplicerat beteende. T.ex. kan två olika värden ge konvergerande funktioner.

Modelleringscykeln: Real world data -> (Modellering, förenkling/avgränsning och göra om till något matematiskt) -> Model -> (Analys) -> Mathematical conclusions -> (Slutsatser) -> explanations predictions -> (Verifiering) -> repeat

<Nu är det pubrunda... (half time)>

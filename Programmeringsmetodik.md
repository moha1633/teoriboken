# Teorihandboken - Programmeringsmetodik (PG)
Studerande: Mohamed abdi ali

## PG 1.1 Versionshantering (Git)
Beskriv rubriken här
Git Versionskontroll, särskilt med verktyg som Git, är en grundläggande del av mjukvaruutveckling och samarbete. Git är ett distributionsformat för versionskontrollsystem som effektivt hanterar ändringar av källkoden över tid. Utvecklare runt om i världen använder det för att spåra och hantera ändringar i sina projekt. Här är en översikt över några nyckelbegrepp och operationer i Git:
Repository : Ett Git-förråd är en samling filer och mappar som utgör ett projekts källkod, tillsammans med all historik och metadata som Git använder för att spåra ändringar.

Commit:En commit är en ögonblicksbild av de ändringar du har gjort i ditt projekt vid en viss tidpunkt. Det är en enhet för att spåra och hantera ändringar i Git. När du vill spara ändringar i ditt lokala arkiv utför du en commit..

Branch (Gren): Grenar Är oberoende utvecklingslinjer. De Kan också ses som versioner av ett projekt. Med hjälp av grenar kan du testa nya funktioner och göra ändringar utan att påverka huvudgrenen (ibland kallad "master" eller "main").

Merge: När du har utvecklat en funktion eller gjort ändringar i en gren, kan du slå samman funktionen tillbaka till huvudgrenen genom en sammanfogning operation.Detta innebär att ändringar från den andra grenen kommer att återspeglas i huvudgrenen

pull Request:En pull-begäran är en mekanism för att föreslå ändringar från en gren till en annan, vanligtvis från utvecklingsgren till mastergren. Andra utvecklare kan granska ändringar och ge feedback innan de slås samman.
Konfliktlösning: Ibland kan konflikter uppstå när Git försöker slå samman ändringar från olika grenar. Detta händer när två ändringar påverkar samma rad i filen. Konflikter måste lösas manuellt.

Push and Pull: Push används för att ladda upp lokala ändringar till fjärrförvaret, medan pull används för att hämta ändringar från fjärrförvaret till en lokal kopia.
Klona: Klona ett arkiv innebär att du skapar en kopia av det på din lokala dator.
Att förstå och kunna använda dessa grundläggande operationer i Git är avgörande för att arbeta effektivt med programvaruprojekt och samarbeta med andra utvecklare. Det finns också många avancerade koncept och funktioner i Git som du kan utforska när du blir mer bekant med den.


## PG 1.2 Benchmarking
Beskriv rubriken här
vad är benchmarking ?
Benchmarking är en strategisk metod som används för att jämföra och utvärdera en organisations prestation, processer, produkter eller tjänster med konkurrenter eller andra ledande företag i samma bransch eller till och med utanför branschen. Syftet med benchmarking är att identifiera bästa praxis, lära av andra och sedan tillämpa dessa insikter för att förbättra din egen prestation, kvalitet och konkurrenskraft.

Inom IT-branschen avser benchmarking jämförelse och utvärdering av olika aspekter av IT-drift, processer och tekniska lösningar för att förbättra prestanda, effektivitet och konkurrenskraft. Här är några specifika områden där benchmarking är vanligt inom IT-branschen.
A) Teknisk Infrastruktur: Inom teknisk infrastruktur involverar benchmarking en djupgående titt på nätverkskapacitet ens bandbredd, serverprestanda (inklusive processorkraft och minne), tillgänglighet och skalbarhet för lagringslösningar samt tillförlitlighet och flexibilitet för analys av molntjänster. Genom att noggrant utvärdera dessa faktorer kan organisationer upptäcka och lösa potentiella flaskhalsar eller ineffektivitet i sin IT-infrastruktur. Det kan innebära att optimera serverkonfigurationen, gå över till effektivare lagringslösningar eller anpassa användningen av molntjänster för att bättre möta företagets behov och krav på tillgänglighet, prestanda och säkerhet.
B)Säkerhet och dataskydd: När det gäller säkerhet och dataskydd möjliggör benchmarking en grundlig bedömning av en organisations säkerhetsarkitektur, inklusive brandväggar, system för intrångsdetektering och krypteringsprotokoll. Det omfattar också en analys av säkerhetspolicyn och förfaranden för att hantera säkerhetshot, incidenter och dataintrång. Genom att jämföra dessa med branschstandarder och bästa praxis kan organisationer identifiera områden där säkerhetsförbättringar behövs. Det kan handla om att införa multifaktorautentisering, utbilda personalen och öka säkerhetsmedvetandet samt införa avancerade verktyg för hotanalys för att förbättra förmågan att upptäcka och hantera cyberhot.

C) IT-tjänstehantering och kundsupport: inom IT-tjänstehantering och kundsupport kan benchmarking användas för att jämföra och bedöma en organisations förmåga att tillhandahålla IT-tjänster och support till användare och kunder. Detta inkluderar analysaspekter som genomsnittlig svarstid, snabb problemlösning, kundnöjdhet och incidenthantering. Benchmarking Mot branschledande standarder och bästa praxis kan hjälpa organisationer att identifiera områden där IT-tjänstehantering och kundsupport kan förbättras, till exempel genom att minska svarstider, förbättra incidenthanteringsprocess och implementera bättre verktyg för övervakning och rapportering av kundnöjdhet.Kan.


## PG 1.3 Testdriven utveckling
Beskriv rubriken här
vad är testdriven utveckling eller TDD ?
Testdriven utveckling(TDD)är en viktig aspekt av programvaruutveckling processen. Detta tillvägagångssätt gör det lättare att testa vad en viss kod gör. Testfall skapas för varje funktion i programvaran och även viss funktioninteklarartestetomarbetaskoden och nykodskapas. Den nya koden måste också klara testerna och vara felfri. Utvecklarna behöver bara skriva nykod om de automatiserade testerna för den koden misslyckas, så att det finns ett testfall för även den minsta funktionaliteten. Och TDD innebär att man utformar och utvecklar tester för varje funktion i applikationen.
Testdriven utveckling (TDD) är en utvecklingsmetod som fokuserar på att skriva tester först,innan man skriver kod. Denna metod har flera viktiga fördelar

A) Testfall-per funktion: TDD skapas testfall för varje del av koden och varje funktion i programvaran. Detta säkerställer att varje del av koden fungerar som förväntat och gör det möjligt att upptäcka fel tidigt i utvecklingsprocessen.
B)Automatiserad Testning: testfall för TDD är vanligtvis automatiserade och körs automatiskt när koden ändras. Det Sparar tid och minskar risken för mänskliga fel.

C)Inkrementell utveckling: TDD underlättar en inkrementell utvecklingsprocess,där koden gradvis byggs upp baserat på testfall. Detta gör att utvecklarna kan identifiera och korrigera fel tidigt i processen.
D)Kontinuerlig integration: TDD fungerar bra med kontinuerlig integration (CI), där kodändringar regelbundet integreras i huvudkudden. Förekomsten av Automatiserade tester gör att vi-processen kan löpa smidigt och effektivt.

E)Kvalitetssäkring: TDD främjar en hög grad av kodtäckning.Det Innebär att testfallen täcker så mycket av koden som möjligt. Detta minskar risken för otestad kod och förbättrar kvaliteten på slutprodukten.
Kontinuerlig förbättring: Genom att använda TDD skapas en kultur av kontinuerlig förbättring inom utvecklingsteamet. Utvecklarna strävar efter att förbättra kvaliteten på koden genom att skriva bättre testfall och identifiera och åtgärda fel i koden.

Sammanfattningsvis är testdriven utveckling en kraftfull metod som främjar ett strukturerat, kvalitetsinriktat tillvägagångssätt för programvaruutveckling. Genom att först skriva testfall och sedan skriva kod som uppfyller dessa testfall kan utvecklarna skapa mer tillförlitlig och robust kod samtidigt som risken för buggar och regressioner minskar


## PG 1.4 Deploy och staging
Beskriv rubriken här
vad är deploy ?
Den kritiska fasen där kodändringar överförs från en utvecklingsmiljö till en produktionsmiljö är deployment, även kallad implementering. Den sista delen av utvecklingsprocessen innebär att utvecklare tar den färdiga koden och gör den tillgänglig för användare. Det är möjligt att deploymentprocessen är komplicerad och kräver noggrann planering och validering för att säkerställa att ändringarna går smidigt och att inga oförutsedda problem uppstår i produktionen.

Deployments Processen består av flera avgörande steg:

A)Preparation: Koden måste förberedas för distribution innan deployment börjar. Att paketera och komprimera filer, skapa säkerhetskopieringar och backuper av databaser och genomföra eventuella ändringar eller korrigeringar i sista minuten är några exempel på vad som kan ingå i detta.

B)Verifiering: Efter förberedelserna måste koden valideras för att säkerställa att den är korrekt och fungerar som förväntat. Innan de går till produktionsmiljön är det nödvändigt att utföra en mängd olika tester, såsom systemtester, integrationstester och enheter, för att hitta eventuella fel.

C)Distribueras: Koden kan överföras till produktionsmiljön när den har validerats och testats framgångsrikt. Det är möjligt att göra detta manuellt genom att överföra filer och uppdatera databaser, eller det kan göras automatiskt genom att använda automatiserade system och verktyg för att effektivisera processen.

D)Observation: Efter distributionen måste de nya tilläggen noggrant övervakas för att se till att allt fungerar som förväntat i produktionsprocessen. Detta inkluderar att spåra prestanda, ta itu med problem eller fel och se till att ändringarna inte påverkar användarna negativt.

vad är stagin?
Staging Miljön är en viktig del av IT-utveckling och används för att testa och validera ändringar av mjukvara innan den släpps live i produktionsmiljön. Utvecklare och testare kan testa hur nya funktioner eller uppdateringar kommer att fungera genom att modellera produktionsmiljön.



## PG 1.5 Debugging
Beskriv rubriken här

## PG 1.6 Dokumentation
Beskriv rubriken här

## PG 1.7 Struktur av kod i projekt
Beskriv rubriken här
vad är Struktur av kod i projekt ? 
Ett projekts kodstruktur beskriver hur och hur koden arrangeras för att skapa programvara. Det är en avgörande del av mjukvaruutveckling eftersom en tydlig kodstruktur gör koden lättare att förstå, underhålla och utöka över tid. En bra kodstruktur ökar också samarbete och effektivitet bland utvecklare som arbetar på samma projekt. Här är några av de viktigaste komponenterna i kodstruktur:

A)Modularisering:Modularisering är processen att dela upp koden i mindre, lättare att hantera delar. Detta innebär att olika funktioner och egenskaper är placerade i separata moduler eller filer. Detta gör koden mer återanvändbar och underlättar felsökning och underhåll.

B) Mappens konstruktion: En mappstruktur som är logisk och konsekvent hjälper till att organisera koden så att det är enkelt att hitta relevanta filer och moduler. Att ha mappar för olika delar av applikationen, som "controllers", "models", "views" osv.

C) Standarder för namngivning: För att göra koden lättare att förstå och underhålla är det viktigt att använda konsekventa namngivningsstandarder för filer, variabler, funktioner och klasser. Utvecklare kan snabbt förstå koden utan att behöva läsa dokumentationen genom att följa standardmetoder.
D) Separation av bekymmer : I enlighet med principen om separation av bekymmer bör olika delar av applikationen, inklusive presentation, affärslogik och dataåtkomst, hållas separata från varandra. Dessutom gör det koden lättare att förstå och ändra.
E) Dekkumantation:För att förklara kodens syfte, funktion och användning måste den kompletteras med kommentarer och dokumentation. Denna funktion gör det lättare för andra utvecklare att förstå och arbeta med koden.

Formatering av kod: Koden blir lättare att läsa och underhålla om den hålls i en konsekvent kod formatering. Utvecklare kan skriva enhetlig kod som är lättare att arbeta med genom att följa en kodningsstandard eller stilguide.Kontroll av versioner: Utvecklare kan samarbeta och hålla reda på ändringar i koden genom att använda en versionshantering plattform som Git. Detta är särskilt viktigt när flera utvecklare arbetar på samma projekt.Automatisk bedömning: Automatiska testfall hjälper till att säkerställa att koden fungerar korrekt och inte bryter upp befintlig funktionalitet när ändringar görs. Detta minskar sannolikheten för buggar samtidigt som kvaliteten på koden förbättras.

Sammanfattningsvis är strukturen av kod i ett projekt avgörande för att upprätthålla en robust och stabil kodbas. Utvecklare kan skapa kod strukturer som uppmuntrar samarbete, underlättar underhåll och möjliggör skalbarhet över tid genom att använda principer som dokumentation, modularisering och namngivningskonventioner.

Staging Miljön spelar flera avgörande roller inom IT-utveckling:

A)Testning och verifiering: En mängd olika tester och valideringar kan utföras i handlings miljön. Dessa inkluderar funktionsprövning, prestandatestning, användaracceptans testning och säkerhetstestning. Utvecklare och testare kan hitta och fixa eventuella problem innan de når slutanvändarna genom att simulera produktionsmiljön.


B)Minimering av risker: Genom att använda stagnation miljön kan företag undvika att göra misstag eller fel i produktionsmiljön. Genom att tillåta ändringar att testas och valideras noggrant innan de släpps live kan problem upptäckas och åtgärdas tidigt, vilket minskar risken för att negativa effekter på användarupplevelsen uppstår.

C) Kommentarer och utvärdering: Innan produktionsmiljön ändras kan hanterings miljön samla in feedback från intressenter och slutanvändare. Detta låter företag göra sista minuten-justeringar eller förbättringar baserat på feedback innan ändringarna släpps live


## PG 1.8 Automatisering av arbetsflöde
Beskriv rubriken här

## PG 1.9 Virtualisering av utvecklingsmiljö
Beskriv rubriken här

## PG 1.10 Bundeling-verktyg
Beskriv rubriken här

## PG 1.11 Terminalinterface
Beskriv rubriken här





källor  

https://github.com/git-guides 

https://kinsta.com/se/kunskapsbas/git-vs-github/  

https://www.consid.com/sv/insikter/artiklar/testdriven-utveckling-skriv-test-forst-och-kod-sen-med-tdd-metoden/ 

https://support.microsoft.com/sv-se/topic/skapa-strukturkoder-i-project-skrivbordsversion-bb6a61aa-debd-4e38-8c04-8e2c1ae3cbda 


https://umbraco.com/knowledge-base/deployment/  

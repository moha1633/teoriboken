# Teorihandboken - JavaScript (JS)
Studerande: Mohamed abdi ali

## JS 1.1 JavaScript / ECMAScript
Beskriv rubriken här

vad är javascript  ?
JavaScript är ett programmeringsspråk som används för att skapa dynamiska och interaktiva webbsidor. Det är ett högnivå, dynamiskt och prototypbaserat språk, så det är ganska enkelt att skriva och använda utan att kompilera det först. JavaScript används huvudsakligen på webbplatser, men det kan också användas för serverapplikationer och spelutveckling.

bakgrund och Forskning
JavaScript skapades 1995 av Brendan Eich på Netscape Communications. Det började som ett enkelt skriptspråk för att göra dynamiska element på webbsidor, men det har utvecklats till att bli ett av de mest använda programmeringsspråken i världen. Ecma International skapade ECMAScript för att göra JavaScript standard. Den första versionen kom 1997. Språkets breda adoption beror på denna standardisering.

vad är Ecmascript ?
ECMAScript, standarden som styr JavaScript, har verkligen utvecklats mycket under åren. Varje ny version av ECMAScript tillför nya funktioner, förbättringar och syntaktiska sockerbitar för att förbättra och effektivisera utvecklingsprocessen. Här är en mer ingående beskrivning av några av de viktigaste egenskaperna och förbättringar som gjordes i några av de mest framträdande versionerna:

A) ECMAScript 6 (ES6) som släpptes 2015.Den tillförde många nya funkioner och ideer som revolutionerade hur javascript kode skrevs  och organiserades. till example 
.Klasser: En syntaktisk komponent som används för att skapa objektorienterade klasser i JavaScript.
.Moduler: Ett modulärt kodstruktureringssystem med inbyggt modulsystem.

B) ECMAScript 2020(ES11):ES11, som släpptes 2020, följde trenden med att lägga till nya funktioner för att förbättra språkets funktionalitet och användbarhet. Den största funktionen var BigInt, som låter dig hantera mycket stora heltal med precision. Dessutom har dynamiska importfunktioner lagts till, vilket gör det möjligt att dynamiskt importera moduler under körtiden. Detta är särskilt fördelaktigt för större applikationer med modulär kodstruktur.


## JS 1.2 JavaScript-ramverk och -bibliotek
Beskriv rubriken här
vad är JavaScript-ramverk och -bibliotek ?

JavaScript-ramverk och -bibliotek är verktyg och samlingar av kod som används för att förenkla utvecklingen av JavaScript-baserade webbapplikationer. För att underlätta utvecklingen av olika delar av en webbapplikation erbjuder dessa verktyg fördefinierade funktioner, komponenter och mönster. En förklaring av skillnaderna mellan ramverk och bibliotek finns här:

vad är ramverk? 
Ramverk
Ett JavaScript-ramverk är en samling verktyg, regler och standarder som används för att styra hur en applikation ska byggas. Det inkluderar modeller, vyer och kontroller (MVC) och en struktur för att organisera och utveckla en applikation, såväl som ytterligare funktioner som autentisering, routing och datahantering. JavaScript-ramverk inkluderar:

A) Angular: ett ramverk utvecklat av Google som ger en fullständig plattform för att skapa dynamiska webbapplikationer med stöd för MVC-arkitektur och tvåvägskoppling.
B) React: ett deklarativt JavaScript-bibliotek skapat av Facebook som fokuserar på komponentbaserad utveckling och effektiv rendering med Virtual DOM.
C) Vue.js är: ett progressivt ramverk för att bygga användargränssnitt som kombinerar prestanda och enkelhet genom att erbjuda en komponentbaserad arkitektur och ett API som är lätt att använda.

vad är bibliotek genom javascript ?
Bibliotek
Ett JavaScript-bibliotek är en samling av inställda funktioner, metoder och verktyg som används för att lösa specifika uppgifter eller problem i en applikation. För att underlätta utvecklingen av specifika funktioner eller delar av en applikation erbjuder biblioteket återanvändbara komponenter och verktyg. JavaScript-bibliotek inkluderar:

A)JQuery: Ett snabbt och enkelt användbart JavaScript-bibliotek som gör DOM-manipulation, händelshantering och animationer lättare.
B) Lodhas: Ett verktygsbibliotek som innehåller arrayer, objekt och funktioner samt hjälpmetoder för datahantering och manipulation.
Moment.js är: Ett bibliotek som kan hantera, ändra och visa data om datum och tid på ett enkelt och flexibelt sätt.
Ramverk är vanligtvis tänkta som kompletta verktygssatser som ger struktur till din applikation, medan bibliotek ger återanvändbara delar och funktioner för att lösa problem.

## JS 1.3 Promises
Beskriv rubriken här

Vad är promises genom javscipt?
Promises är en väsentlig komponent i JavaScripts asynkrona natur och har utvecklats till en väsentlig komponent i dagens webbutveckling. De är avgörande för att hantera asynkrona operationer som nätverksbegäranden, databasåtkomst och andra I/O-operationer som tar längre tid att slutföra.

Promises ger utvecklare många fördelar. För det första erbjuder de ett enhetligt sätt att hantera både framgångsrika och misslyckade resultat, vilket gör det enklare och mer förutsägbart att hantera asynkrona operationer. Detta gör koden mindre komplex och gör den lättare att läsa och underhålla.

En annan fördel med Promises är möjligheten att kedja flera asynkrona operationer efter varandra, vilket gör att olika steg i en applikation kan utföras sekventiellt. Detta görs med hjälp av.then()-metoden som anger vilken kod som ska köras när en Promise uppfylls och.catch()-metoden som hanterar eventuella avvisade löften.

Genom att dela upp logiken för att hantera framgång och misslyckande av en asynkron operation, främjar löften också bättre felhantering. Detta gör det lätt att skilja mellan olika typer av fel och vidta lämpliga åtgärder beroende på omständigheterna.

Sammanfattningsvis är Promises en kraftfull mekanism som gör att asynkrona processer i JavaScript kan hanteras effektivt. De hjälper till att göra JavaScript-kod mer robust, läsbar och underhållbar genom att erbjuda en strukturerad och konsekvent metod för att hantera asynkronitet. Promises fortsätter att vara en viktig del av utvecklarverktygslådan för att skapa responsiva och kraftfulla webbapplikationer trots den ökande komplexiteten i moderna webbapplikationer.



## JS 1.4 OOP i JavaScript
Beskriv rubriken här

vad är OOP i javascript ?
Objektorienterad programmering (OOP) är en metod för programmering som lägger stor vikt vid att organisera kod kring objekt, som är representationer av verkliga eller abstrakta entiteter och deras interaktioner. OOP i JavaScript låter utvecklare skapa kod som är mer modulär, återanvändbar och underhållbar genom att organisera den runt objekt och klasser.

Inkapsling, en viktig princip inom Open Source Programming (OOP), innebär att data (egenskaper) och tekniker för att arbeta med dem är sammankopplade i ett objekt. Genom att begränsa tillgången till vissa delar av koden och förhindra oönskad datamanipulation, stödjer detta idén om att göra koden mer robust och säker.
En klass kan ärva metoder och egenskaper från en annan klass genom arv, en ytterligare viktig komponent i Open Source Programming (OOP). Detta ökar återanvändningen av kod och minskar behovet av kodduplikationer. JavaScript använder vanligtvis prototypkedjor och prototyphierarkier för att implementera arv.

En annan princip inom Open Source Programming (OOP) som kallas polymorfism tillåter objekt att bete sig på olika sätt beroende på vilken typ av objekt de är. Detta kan uppnås genom att kombinera tekniker som är identiska i olika klasser men som används för olika ändamål.

JavaScript-utvecklare kan skriva kod som är mer strukturerad, lättläst och underhållbar genom att använda dessa OOP-principer. OOP i JavaScript är särskilt användbart när man bygger större och mer komplexa webbapplikationer, där en tydlig kodstruktur och organisering är avgörande. JavaScript-utvecklare har nu bättre verktyg för att implementera objektorienterade koncept i sin kod med klassens införande i ECMAScript 2015 (ES6).


## JS 1.5 DOM-manipulation
Beskriv rubriken här

## JS 1.6 HTTP-requests
Beskriv rubriken här

## JS 1.7 Lexical scope
Beskriv rubriken här

## JS 1.8 Event handling
Beskriv rubriken här

## JS 1.9 Prototype inheritance
Beskriv rubriken här

## JS 1.10 Higher-order functions
Beskriv rubriken här

## JS 1.11 Single-thread programming
Beskriv rubriken här

## JS 1.12 OAuth från frontend
Beskriv rubriken här

## JS 1.13 Websockets
Beskriv rubriken här




källor 
https://redcapes.se/vad-ar-javascript-och-vad-gor-spraket/ 

http://htmlhunden.se/dist/full.html#04-01-js-intro
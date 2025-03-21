# Individuella reflektioner

Svara på var och en av frågorna nedan individuellt (minst 100 tecken per fråga)

## Frågor

### Inledning

#### Vad var ditt mål med projektet initialt?

För det första bestämde jag mig för att anta rollen som utförare och undvika att gå in i en ledarroll (jag var inte scrum master). Jag har en tendens att ta plats och leda om jag ser att ingen annan gör det, eller om någon gör det bristfälligt. Som utförare ville jag utföra mina uppgifter i tid och på ett sätt som skulle underlätta för den som eventuellt behövde förstå det jag hade gjort. Jag bestämde mig också för att be om hjälp och att vara behjälplig. Jag ville också uppmuntra att vi höll oss till den agila arbetsmetodiken. Vidare var ett övergripande mål att fortsatt hålla mig till att arbeta strukturerat, något som den agila metoden verkligen uppmuntrar. En sak i taget och inte mer än jag klarar av för att kunna fortsätta arbeta strukturerat.  

#### Vad var din känsla inför att arbeta i ett team när du gick in i uppgiften?

För mig innebär det alltid en viss oro innan jag vet hur gruppen kommer att samarbeta. Kommer alla göra det de säger att de ska göra? Kommer någon undvika arbeta?  Kommer någon annan vara borta mycket? Kommer det bli konflikter som tar energi och kraft? Kommer jag bli påverkad av detta och bli på dåligt humör? 

### Planering och genomförande

#### Hur tycker du att planeringen inför projektet fungerade?

Vi konstaterade snabbt att den här typen av applikation skulle ta mer än två sprintar att utföra i sin helhet och att vi behövde göra vissa avvägningar för att helt enkelt komma igång. Jag tycker att hela gruppen var på samma bana när det gällde detta och att det inte var några problem att göra de avvägningar som krävdes. Vi ordnade snabbt upp de återstående skisserna i figma; vilket var ganska enkelt då den grafiska profilen redan var satt. Vi var mycket samspelta redan från början. 

#### Vad har du bidragit med i planeringen, samt utvecklandet av applikationen.

Planering 

Jag upplever att jag har en väl utvecklad förmåga att kunna se helheter och undvika att fastna i detaljer. Av erfarenhet vet jag hur viktigt det är att inte fastna i finslipande för tidigt i ett projekt tex. Jag bidrog med att se i vilken ordning “user stories” borde göras, dels utifrån hur vi kunde göra det rent tekniskt, men inte minst utifrån vad som var strategiskt att visa produktägaren på första sprinten.  

Utveckling 

Jag gjorde Figma-skisser på drop-down från kundvagn och hamburgermeny, samt tillägg till den befintliga menysidan. Jag skissade också upp about-sidan. 

Det första större uppgiften jag kodade var själva menysidan, som byggs utifrån ett API. Viktigt här var att det skulle vara lätt för den som byggde kundkorgen att hämta data vi klick på artiklar. Jag tyckte det var en bra uppgift med tydlig ingång och leverans. 

Den andra större uppgiften var “about us” sidan; en avgränsad uppgift som inte krävde mycket mer än att den skulle stämma överens visuellt med övriga sidor. Här gjorde jag också en footer som sedan också användes på andra sidor. 

Jag la sedan till filtrering på mat, dip och dryck på menysidan. 

Efter användartester vi genomförde efter första Sprint Review skapade jag tydligare feedback för användaren då den klickar på något i menyn. Dels genom färgkodning , men också genom en siffra på kundkorgen som visar antalet artiklar.  

Jag kodade också sidan som visar en användares orderhistorik.  

Utöver detta blev det endel buggfixar. 

#### Beskriv med dina egna ord, er applikation

Det är en appikation för att beställa mat. Du registrerar dig som användare, du kan i efterhand också ändra dina användaruppgifter. Användaren lägger ordrar genom att klicka i en meny. Det du klickat på samlas i en kundkorg, från vilken du kan ta bort och lägga till antal artiklar. Från kundkorgen klickar användaren sig vidare till kassan. I kassan kan man också lägga till och ta bort från antalet artiklar. I kassan kan man klicka “take my money” för att komma vidare till orderbekräftelsen där man också får info om leveranstid. Här kan man också klicka sig vidare till kvittot. Går man in på sin profil så kan man titta på sin orderhistorik. 

På “about-sidan” kan man se mer om företaget och mer om hur det fungerar. Det finns också en “hitta oss” sida som visar var bilen för tillfället befinner sig. Det finns också möjlighet att logga in som admin. 

### Teamets utmaningar och lösningar

#### Vika var de största utmaningarna för dig?

Det jag la mest tid på var menysidan som jag skapade från grunden med befintlig figma-skiss som referens. Svårigheten här var att börja i rätt ände och göra en sak i taget. 

En annan utmaning var att lägga till siffran som visar antalet artiklar i kundkorgen. Detta var komplicerat eftersom det krävde att jag behövde navigera mycket i andras kod. Jag tycker fortfarande det är svårt att läsa kod, men upplever att jag blir succesivt bättre på det. 

#### Hur löste eller hanterade du dessa utmaningar?

Jag skissade flexbox-strukturen med penna och papper och kodade sedan menyn statiskt. Jag använde sedan Template Literals för att generera menyn utifrån API anrop. Jag var noga med att det skulle vara skalbart. Om något ändras i API:et så slår det igenom på menyn direkt. 

När det kommer till att lösa uppgifter som kräver att läsa andras kod, upplever jag att det också handlar om att arbeta strukturerat och metodiskt. Vårt projekt innehöll många mappar och filer och jag behövde arbeta koncentrerat och strukturerat för att förstå sammanhangen. I de fall jag inte förstått kod har jag frågat och alla har varit behjälpliga. 

#### Vilka kompromisser inom teamet har du fått göra under projektets gång?

Jag har försökt tänka brett och inte gå in i detaljer kring exempelvis visuella detaljer. Jag tycker applikationen ser bra ut, men att den har vissa brister på det planet. Jag har medvetet valt att inte fokusera för mycket på det; speciellt inte på det som andra har tagit fram. 

Jag hade gärna sett att vi gjorde funktionsanrop till samtliga sidor i main.js (med villkor i stil med: window.location.pathname.includes('index.html')). Jag tror det hade underlättat att navigera i koden. Det svävade iväg lite med .js filer för varje enskild sida. Det var dock inget större bekymmer.  

### Individuell reflektion och utvärdering

#### Vad lärde du dig under projektets gång?

Det är tydligt att jag trivs under bra och tydlig ledning och med kompetenta medarbetare. I det här projektet kunde jag verkligen koppla av och i lugn och ro lösa de uppgifter jag tagit på mig utan att oroa mig för hur det gick för de andra. Jag kände ingen stress alls under arbetet, vilket är väldigt ovanligt för mig när det kommer till grupparbete. Jag har ett starkt kontrollbehov, men det vållade inga problem i den här gruppen. 

Jag trivs bra med att arbeta på egen hand och i grupp, om gruppen fungerar. Detta är en av de bästa gruppkonstellationer jag har upplevt. 

#### Finns det någonting du skulle velat göra annorlunda om du fick chansen igen?

Jag skulle ha tittat på all kod mer kontinuerligt redan från början av projektet. Det hade underlättat i arbetet med att pussla in mina egna delar. 

Jag hade också velat lägga mer tid på mappstruktur och logik, innan man sätter igång att koda. Dock var tiden nog lite för knapp för det i det här projektet. 

#### Vilka möjligheter ser du med de kunskaper du fått under arbetet med projektet?

En fungerande grupp där alla tar ansvar är mycket viktig för att ett projekt ska lyckas.  

Vi hade en fin reflektion i vår sista Sprint Retrospective där var och en pratade om hur vi såg på oss själva, vad vi tycker om grupparbete etc. Jag tror det kan vara bra att ha sådana samtal tidigt i ett projekt så att man lär känna varandra lite bättre. sådana samtal verkar avväpnande; öppnar sig en så öppnar sig flera. Klimatet blir öppnare och man vågar mer. 

### VG-frågor (minst 200 tecken)

#### Beskriv minst tre fördelar med att arbeta agilt och motivera varför de är viktiga. Använd exempel från ert projekt för att styrka dina argument.

Jag upplever att Daily Scrum på morgonen är väldigt effektivt för att hålla ett driv i arbetet. Jag blir motiverad av att behöva presentera vad jag har gjort på en daglig basis. Dels skapar det lite press och dels synliggör det vad man faktiskt har gjort. Det ger tillfälle till reflektion, vilket jag tycker är viktigt och lätt att glömma, speciellt om arbetssituationen är pressad. I min roll som gruppledare i arbetslivet har jag ibland ställt in den typen av möten för att spara tid, det kommer jag undvika att göra i framtiden. I projektet tvingade mötena fram en konkretisering av det jag höll på med, vilket var viktigt för att komma vidare själv eller med hjälp av andra. 

Att arbeta mot en Sprint Review tvingar projektet till att strukturera upp arbete på ett bra sätt. Vikten av att presentera något för produktägaren på veckobasis driver arbetet framåt och tvingar fram en planering av arbetet. Jag började genast tänka kring hur vi från dåvarande utgånspunkt skulle kunna presentera ett så bra resultat som möjligt för produktägaren på nästkommande Sprint Review. Det blir ett tydligt kundfokus hela vägen i projektet. Viktigt att tänka på här är att man inte behöver ha löst allt rent tekniskt, det kan räcka med statiska representationer. Att ha statiska representationer underlättar också arbetet med de tekniska lösningarna. Man bör alltid börja i Figma. 

Sprint Review är bra för att summera arbetet som gjort under en längre tid. Ett utmärkt verktyg för att identifiera sådant som har fungerat bra och sådant som har fungerat mindre bra. Jag tror att dessa möten liksom de dagliga Scrum ser till att hålla gruppmedlemmarna på tårna och skapa ett driv framåt. Det är viktigt för de flesta att känna att de bidrar till gruppens och projektets bästa. Jag upplever att de reflektioner gruppmedlemmarna bjöd på under dessa möten hjälpte till att skapa en familjär och trevlig stämning i gruppen, där man kunde känna sig trygg. 

#### Beskriv en konkret lösning du föreslagit under projektet. Varför ansåg du att den var bäst? Jämför med minst en annan möjlig lösning och förklara varför du inte valde den.

Eftersom min första uppgift var att ta fram menyn blev jag tidigt involverad i diskussionen kring hur vi skulle hantera specifika användare och specifika användares ordrar, samt orderhistorik. Jag var inte ensam med tanken att varje användare skulle lagras som objekt med olika egenskaper, bland annat objekt med arrayer för att lagra dels nuvarande order, men också för att lagra orderhistorik.  Vi hade diskussioner om hur detta skulle lösas, men jag kan inte minnas att vi hade olika lösningar som vi diskuterade. Det handlade mer om att komma fram till en gemensam lösning i samförstånd.

#### Ge minst två exempel på lösningar ni valde bort. Analysera varför ni avstod från dem. Hur påverkade det projektet? Kunde något ha gjorts annorlunda?

Att bygga menyn statiskt istället för att hämta den från ett API 

Vi ville att menyn skulle vara dynamisk och lätt kunna uppdateras utan att ändra koden manuellt. Genom att hämta menyn via ett API kunde vi säkerställa att alla uppdateringar skulle reflekteras automatiskt. Lösningen vi valde innebar en del extra arbete i början för att strukturera API-anropen och hantera data korrekt, men det gav oss en mer flexibel lösning. Om vi hade byggt menyn statiskt, hade vi sparat tid i början men fått problem längre fram om menyinnehållet behövde ändras.

Att använda en databas istället för Local Storage för att spara användaruppgifter och orderhistorik 

Att implementera en riktig databas hade varit mer robust, men vi hade begränsad tid och erfarenhet. Local Storage var en enklare lösning som ändå fungerade för vårt ändamål. 
Local Storage fungerade bra, men det hade begränsningar, exempelvis kan en användare inte se sin orderhistorik om de byter enhet. Hade vi haft mer tid, hade vi implementerat en serverbaserad lösning för att hantera data mer långsiktigt.   

#### Reflektera kring hur den kod du bidragit med skulle kunna förbättras, ge konkreta exempel.

Hade jag haft mer tid och känt att jag hade stenkoll på all kod så hade jag velat rensa upp i den css jag och de andra skrev. Vi hade en gemensam style.css och sedan separata css-filer för samtliga sidor. Jag hade gärna lagt tid på att återanvända stilar från huvudfilen mycket mer än vi gjorde, dels för att det skulle resultera i mindre kod men inte minst för att det visuella intrycket skulle blivit mer enhetligt. 

Min filterMenu() är onödigt lång och jag inser att den innehåller flera upprepningar. Jag lät ChatGPT titta på den och föreslå ändringar. Men eftersom det var några steg där som jag inte förstod bestämde jag mig för att lämna den som den var. Hade jag haft mer tid hade jag satt mig in i det mer.  

#### Om ni hade en vecka till på er, vad skulle du ändrat? Fokusera på arbetsprocessen, samarbetet eller verktygen ni använde. Hur skulle det ha påverkat resultatet?

Den veckan hade jag lagt på att strukturera mappstrukturer och logik kring koden. Det blev ganska stökigt och svårt att följa till slut. Eftersom vi alla var nya på detta hade det dock varit svårt att veta vikten av detta. Det är lätt att vara efterklok och är snarare fråga om något för lessons learned. Jag tycker att vår applikation håller ihop på ett bra sätt, men det hade varit ännu bättre om strukturen på .css och .js filer hade varit tydligare.  

Jag tycker att vi hann med väldigt mycket med tanke på den korta tiden, så en vecka till hade mest inneburit buggfixar och städning.  

Det hade varit roligt att använda en databas istället för Local Storage. Hade vi haft en vecka till så kanske vi hade kunnat lösa det. 

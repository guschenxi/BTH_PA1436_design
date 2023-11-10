---
Title: Loads
Description: Here is Report page of loads
---


Rapporten på prestandaanalysering av tre länstrafikbolags webbplatser
=======================

I denna rapport har jag jämfört tre webbsidor med hjälp av några verktyg. Jag har dokumenterat och analyserat deras webbsidors prestanda, laddningstider, webbsidors storlek, osv.

Urval
-----------------------

Från början ville jag analysera samma personsidor i alla tre uppgifter, därför ville jag välja alla tre sidor samma som förra uppgiftens:
1. ~~https://mikaelroos.se/~~
2. ~~https://emilfolino.se/~~
3. ~~https://taylorvowell.com/~~

Men det visade sig att Mikael Roos:s webbsidan gick inte köra i testverktyget, samt Emil Folinos och Taylor Vowells webbplaster innehåller inte mer än en webbsida. Därför uppfyller de tre webbplatserna inte uppgiftens krav. Så jag fick göra om urvalet.

Eftersom jag arbetar inom kollektivtrafik, tänkte jag att det kan vara bra att testa och analysera hur bra länstrafikens webbplatser fungerar. Jag valde de tre länstrafikbolagen som är närmaste Blekinge Tekniska Högskola:
1. [Kalmar Länstrafik (KLT)](https://kalmarlanstrafik.se)
2. [Blekingetrafiken (BT)](https://blekingetrafiken.se)
3. [Länstrafiken Kronoberg (LTK)](https://lanstrafikenkron.se)

De här tre länen är grannlän och det finns många resenärer som reser varje dag över länsgränserna till och från de tre länen. Deras webbplaster är viktiga för resenärerna att få trafikinformation, information om biljetter och priser samt information om hur man når kundservice. Därför valde jag att analysera deras hemsidor, sidor för biljetter och priser, och sidor för kundservice.


Metod
-----------------------

För att dokumentera webbsidornas prestanda använde jag ett verktyg som heter ["PageSpeed Insights" (https://pagespeed.web.dev/)](https://pagespeed.web.dev/) som erbjudes av Google. Verktyget ger betyg på anvigna webbsidans prestanda, tillgänglighet, och andra mätbara ämnen, för både mobilenheter och desktopenheter. Verktyget ger även användbara förslag på vilka saker man bör optimera för att öka webbsidans prestanda. Nedanstående bilden visar hur PageSpeed visar en webbsidas testresultat.

![bild: PageSpeed exempel](../image/pagespeed.png "PageSpeed exempel"){.page-capture}

Ett annat verktyg som jag använde var den inbygda DevTools i webbläsaren Chrome. Jag använde "Network"-flik för att testar webbsidornas laddningstider, totala storlek och antal laddade resurser. Nedanstående bilden visar hur de önskade mätade värden visas i verktyget. Jag testkörde varje webbsida tre gånger och tog snittet av de tre mätvärden för laddningstid. 

![bild: Network exempel](../image/verktyg_network.png "Network exempel"){.page-capture}

Resultat
-----------------------
Testresultatet dokumenteras i nedanstående tabellen.

<iframe width="80%" height="320px" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSsu18QhBXykCeEu0CP_PfTa3hwqWf4ky0RJ12RnwxLO1GL60iIZBLyUgaPKI39FsVaXkDP5wtUByBF/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>

### Kalmar Länstrafik (KLT)

![bild på Kalmar Länstrafiks hemsida](../image/klt_desktop.png "bild på Kalmar Länstrafiks hemsida"){.page-capture}

** Hemsidan **

Sidan har fått ganska hög betyg - 86 - för mobilenheter, och sämre betyg - 66 - för desktop. Genomsnitt laddningstid är 1.19 sekunder, antal resurser är 50 och totala storlek är 2.8 MB.

** Biljett-informationssidan **

Sidan har fått ganska hög betyg - 76 - för mobilenheter, och även bättre betyg - 89 - för desktop. Genomsnitt laddningstid är 0.91 sekunder, antal resurser är 46 och totala storlek är 1.7 MB.

** Kundservice-sidan **

Sidan har fått ganska hög betyg - 76 - för mobilenheter, och mycket bra betyg - 91 - för desktop. Genomsnitt laddningstid är 1.06 sekunder, antal resurser är 40 och totala storlek är 2.6 MB.

** Enligt testresultatet har webbplatsen ganska bra prestanda på både mobilenheter och desktop. Laddningstider är rimliga, runt 1 sekund, den totala storleken är inte för stor. Man kan ta bort oanvända Javascript-koder för att göra sidan ännu mer optimerad. **

### Blekingetrafiken (BT)

![bild på Blekingetrafikens hemsida](../image/bt_desktop.png "bild på Blekingetrafikens hemsida"){.page-capture}

** Hemsidan **

Sidan har fått dålig betyg - 37 - för mobilenheter, men ganska hög betyg - 73 - för desktop. Genomsnitt laddningstid är 2.8 sekunder, antal resurser är 83 och totala storlek är 7.0 MB.

** Biljett-informationssidan **

Sidan har fått medium betyg - 55 - för mobilenheter, men ganska hög betyg - 78 - för desktop. Genomsnitt laddningstid är 1.2 sekunder, antal resurser är 48 och totala storlek är 3.6 MB.

** Kundservice-sidan **

Sidan har fått medium betyg - 56 - för mobilenheter, men mycket bra betyg - 90 - för desktop. Genomsnitt laddningstid är 1.25 sekunder, antal resurser är 40 och totala storlek är 3.1 MB.

** Det verkar som att Blekingetrafikens webbsidor generellt fungerar sämre än KLTs webbplats, eftersom den har lägre betyg och längre laddningstider. Alla tre sidor fungerar mycket bättre på desktop än på mobilenheter. Hemsidan fungerar sämre än andra två sidor, eftersom den har dubbellängre laddningstid och dubblad resurser samt storlek. Webbplatsen kan förbättras genom att ta bort oanvända Javascript-koder, och använda storlekminskade bilder särskilt för mobilenheter. **

### Länstrafiken Kronoberg (LTK)

![bild på Länstrafiken Kronobergs sida](../image/ltk_desktop.png "bild på Länstrafiken Kronobergs sida"){.page-capture}

** Hemsidan **

Sidan har fått dålig betyg - 32 - för mobilenheter, och medium betyg - 68 - för desktop. Genomsnitt laddningstid är 4.41 sekunder, antal resurser är 173 och totala storlek är 9.3 MB.

** Biljett-informationssidan **

Sidan har fått ganska dålig betyg - 51 - för mobilenheter, och medium betyg - 71 - för desktop. Genomsnitt laddningstid är 3.64 sekunder, antal resurser är 130 och totala storlek är 5.3 MB.

** Kundservice-sidan **

Sidan har fått ganska dålig betyg - 53 - för mobilenheter, och medium betyg - 74 - för desktop. Genomsnitt laddningstid är 3.17 sekunder, antal resurser är 124 och totala storlek är 5.4 MB.

** LTKs webbplatsen fungerar generellt sämre än de andra två webbplatserna, eftersom den har mycket lägre betyg och mycket längre laddningstider. Alla tre sidor fungerar sämre på mobilenheter än på desktop. Hemsidan fungerar sämst bland alla tre sidor, eftersom den har mycket mer resurser att ladda in och storleken är mycket större. Webbsidorna kan optimeras genom att ta bort oanvända Javascript-koder, ändra bildformat från JPG, PNG till WebP samt använda minskad storlek för bilderna på mobilenheter, ta bort oanvända CSS-koder. **

Analys
-----------------------

1. Webbsidas laddningstid är proportionell mot antalet resurser som ska laddas in och den totala storleken av websidan. Därför är det viktigt att ha koll på den totala storleken och antal resurser, om man vill minska laddningstid. T.ex. onödiga resurser, css, javascript bör inte laddas in och bilder samt videos storlek ska minskas så mycket som möjligt, om det inte kraftigt påverkar kvalitet.

2. Webbsidor lär lätt få lägre betyg och fungerar sämre på mobilenheter än på desktop, eftersom man lär glömma att göra speciella design åt mobilenheter. Därför är det ännu viktigare att testköra webbsidor på mobilenheter, ta bort önödiga resurser och minska webbsidors storlek när det gäller webbdesign för mobilenheter. Det räcker inte med att bara göra om CSS så att webbsidorna är responsiva, utan man måste tänka på t.ex. använda storlekminskade bilder på mobilenheter, ta bort onödiga effekter på mobilenheter, osv.

3. Hemsidans kvalitet spelar en viktig roll i att dra användarens uppmärksamhet. Men hemsidan lär lätt bli mycket större än andra webbsidor i en webbplats, eftersom man vill ha så mycket information som möjligt att placeras på hemsida. Men är all information helt nödvändig att visa på hemsidan? Kansken inte alltid. Därför som en webbdesigner bör vi lära oss att göra avvägningar. Endast mycket viktiga innehåll ska placeras på hemsidan och ikke-superviktig information kan placeras på andra sidor i webbplatsen. En snabbladdad hemsida spelar också en avgörande roll i att göra användaren stanna kvar.

4. Kalmar Länstrafiks webbplats är otvivelaktigt vinnare i testet. Blekingetrafikens webbplats ligger på andra plastsen, medan Länstrafiken Kronobergs webbplats är sämst bland alla tre.


Övrigt
-----------------------

Xi Chen skrev denna rapport ensam

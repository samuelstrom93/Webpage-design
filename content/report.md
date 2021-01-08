---
Title: Report
Description: Report page.
Template: report
Hidden: true
---

Report
==========================

## Uppdrag 2: Tema

## Färgpaletten och valda färger.

I tidigare kmom när vi analyserade så använde jag mig av Hermés webbplats. Där hittade jag en bakgrund som jag gillade väldigt mycket. Den färgen blev min grundbult och syns i färgpaletten nedan med en svart ram runtom. Det är min huvudsakliga bakgrundsfärg i originaltemat. För att hitta färger som kompletterade den så valde jag att använda mig av Adobes färgsnurra och använda komplementär som färgharmoni och matade in färgen. Utifrån det fick jag färger som jag använder i variabler i scss-filen style.

<p><strong>Färgpalett</strong></p>
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; border: 1px #000 solid; background-color: #f6f1eb">
</td><td style="height: 50px; width: 50px; background-color: #fff">
</td><td style="height: 50px; width: 50px; background-color: #a89e91">
</td><td style="height: 50px; width: 50px; background-color: #cabead">
</td><td style="height: 50px; width: 50px; background-color: #809ba8">
</td></tr>
</table>


## Typografin, designprinciper och designelement

**Typografi**

Jag har använt mig av fonten **Inter** för brödtext och i princip all text förutom rubriker. Det är en font som Emil visade på en föreläsning som jag gillade väldigt mycket. Den passar väl för dataskärmar och har en hög x-axel som hjälper läsbarhet mellan gemener och versaler. Helt enkelt är den väldig enkel och simpel i sitt utförande och har en god läsbarhet. Jag har även försökt att jobba med avstånd så att det blir tydligt mellan texten.
För mina rubriker valde jag **Bree Serif**. För att kontrasera den läsbara och enkla inter-fonten så valde jag när jag sökte på Google fonts att leta efter en för *display*. Det gjorde att det stack ut lite mer och blev inte så platt och tråkigt som brödtexten var.

I övrigt har jag försökt jobba med fet text där det behövs för att accentuera, understreck för att visa länkar eller vald länk t.ex eller en typ av horizontal rule (hr-element) för att separera stycken. Den hittade jag bland annat på Codepen och var i själva verket en ihopsättning av div och hr.

**Designprinciper**

När man skapar en hemsida så blir det indirekt att man använder sig av väldigt många designprinciper. Nedan ska jag ta med de som jag tycker är dominerande på min sida och som jag särskilt haft i åtanke.

*Linjer*

Jag har använt mig mycket av linjer (div med hr-element) för att hjälpa till att dela in sidan i olika stycken eller delar som hör ihop med varandra. På så sätt blir det inte rörigt för ögat när man ska försöka kategorisera sidans olika delar.

*Färg*

Som nämnt ovan har jag jobbat med Adobes färgsnurra och använt kompletterande färger för att skapa en färgharmoni. Sedan har jag försökt använda färgpaletten konsekvent med en särskild färg för länkar och knappar och en annan för bakgrunden till bilder och figcaption t.ex.

*Balans*

På Home- och about-sidan så har jag jobbat med att balansera upp bilder och text så att de den totala ytan som täcks både till höger och vänster är balanserad även fast det inte är symmetriskt. Det gör att intrycket blir mer av ett *organiserat kaos*.

*Hierarki*

Indirekt kan man säga att jag jobbat med hierkarkier. Genom att ha en rubrik för Home t.ex. så får man en förståelse för att det rör saker som hör hemma på förstasidan. Sedan har jag text eller bilder som är del av det andra lagret och sedan med linjer kan jag separera dessa hierarkier och komma till ett till andra lager i form av projekten som ligger på förstasidan och det tredje lagret med projekt att klicka på, knappar och text.

*Rörelse*

För att få ett livligt intryck har jag använt mig av interaktivitet. Det både i navigationsfältet där jag genom att hålla över nav-länken för två linjer som rör sig in mot länken och ger rörelser. Sedan har jag hittat en effekt som jag gillar att när man håller över en av mina projekt med bild och text så använder jag mig av <code>transform: scale(1.05)</code> med en 0.4s animation vilket ger en lite häftig känsla av att det händer saker och att här kan jag klicka.

*Djup*

På mina projektbilder på både home- och highlights-sidan har jag använt mig av skugga för att ge en extra dimensionen i dubbel bemärkelse så att hemsidan inte upplevs så platt och enkel. När man väl håller över och bilden förstoras så försvinner skugan på ett lämpligt sätt.

*Grid*, *symmetri*, *repetition*

Jag klumpade ihop dessa designprinciper då de i mitt projekt haft mycket gemensamt. På highlights-sidan har jag använt mig av CSS-grid för att på ett snyggt sätt strukturera ihop alla projekt med samma layout, skapa en symmetri och repetition. 

För att ha en konsekvent design och repetition som gör att man känner igen vissa företeelser mellan sidor har jag som nämnt återanvänt färger men också färger för länkar, bakgrunder och runda kanter på de flesta div-elementen så att användaren känner igen sig och förstår vad vissa knapptryck gör. Användaren ska inte behöva tänka för mycket helt enkelt utan designen ska vara konsekvent och förståelig.


## Känsla med webbplatsen.

Jag valde kund 3 i uppgiftsbeskrivningen som är **egenföretagaren Bew Gorp**. Han har ett fokus på webbutveckling och alla dess aspekter och sidan som jag gjort i projektet ska vara en typ av CV-webbplats eller portfoliosidan för att kunna visa upp för sina potentiella kunder.

Kunders olika behov skiljer sig såklart men en tydlig trend som jag uppfattat är att ha en minimalistisk design med ett tydligt fokus på användarvänlighet. Därför tänker jag genom att få portfoliosidan att se ut som en stor del av kunderna vill kan man redan locka in flertalet kunder bara med designen. T.ex. med att jobba mycket med mycket negativt utrymme och de nämnda designprinciperna ovan. Färgharmonin tog jag ifrån Hermés och är ett färg som jag tycker funkar bra för att få ner mer lyxighetskänsla.

En viktig del av en portfoliosida är fokus på rätt saker. Det är viktigt att tydlig info om webbutvecklaren Jerry Swift är i fokus och är lätt att hitta för att få hans drivkrafter, motivation men också erfarenhet. Det andra viktiga är tidigare projekt och därför kan man hitta all den nämnda info redan på förstasidan så att ingen potentiell kund missar denna viktiga information. Sedan kan man klicka sig vidare snabbt för att se dessa projekt via highlights i nav-fältet eller via knappen nedanför projekten. 

Då en webbutvecklare bör förmedla ett kreativt intryck har jag använt mig av bilder för att anspela på färger. T.ex. flash-bilden högst uppe i navigationsfältet är massa färger och en av bilderna på about-sidan är rollers och massa färger. Det ska ge ett intrycket av kreativitet som potentiella kunder förhoppningsvis ska gilla. 





## SASS 

Jag har försökt att göra det så enkelt som möjligt med SASS-koden. Delar av koden som inte skiljer sig emellan vilka sida man är inne på såsom header, nav, footer, typography och olika style är egna sass-moduler som berör namnets del. Sedan för varje sida har jag skapat en egen sass-modul så att ändringar i about görs i report.scss. På så sätt är det enkelt att hitta rätt ställe att justera koden för rätt ändringar i designen. I t.ex. header-modulen har jag importerat nav-delen som är en mindre del av headern för att ännu mer modularisera koden och göra den mer läsbar när jag vill göra ändringar.


<div class="sb sb-home">
      <small></small>
      <hr class="section-break-3" />
</div>

<section class="ss-style-doublediagonal-index"></section>


## Uppdrag 3: Responsivitet och tillgänglighet

## Responsivitet

Jag har primärt arbetat med Firefox som webbläsare men också Chrome för bl.a. Lighthouse. För att jobba med responsiviteten har jag, utöver vanliga webbklienten, jobbat med Ipad och Iphone X/XS i Firefox dev tools. På alla mina sidor har jag använt mig av CSS-grid för att presentera innehållet vilket gjort att arbetat med att göra webbsidan responsiv är tämligen enkelt. Där har jag arbetat med media-queries för <code>max-width: 992px</code> och <code>max-width: 767px</code> för att få med nämnda enheter ovan. Jag har på något ställe lagt till en media-query på 1200 px för att gap i griden ska te sig bättre. I 992px media-query så har jag börjat använda mig av att elementen i griden använder sig av t.ex. <code>grid-column: span 3;</code> om griden har tre kolumner för att fylla ut hela då elementen annars hade komprimerats ihop och blivit oläsbart.

Jag har använt mig av flexbox för någon enstaka div då det är smidigt med att positionera elementen där man vill inuti en div.

Ingen av sidorna har någon horisontell scrollbar utan anpassas lämpligt i griden.

I alla bilder som används på sidorna har jag använt mig av cimage och picture-element med <code>srcset</code> för lämpliga bildhantering för mindre enheter.


## Tillgänglighet 

När jag testade att göra Lighthouse-test för tillgängligheten så var alla sidor redan mellan 95-100 så det var inte så mycket som behövdes göra. Det som behövdes ändras var bland annat att lägga till <code>html lang</code> i html-elementet och ändra om dold tab-element <code>aria-hidden="true"</code> samt <code>tabindex</code> med högre värde än ett. Sedan har jag har sedan tidigare fått erfara att hierarkier med rubriker (h1, h2 och h3) behövde komma i ordning på sidan. Jag har t.ex. försökt använda det här i mina markdown-filer med att ha rubriker och sedan en underrubrik som h2 eller h3 och sedan längre ner på sidan en h1 igen men för att tydliggöra ett nytt ämne/område men det har inte Lighthouse gillat så därför har jag jobbat med fetmarkering eller kursiv text för detta istället.

*Färgblindhet*

Jag använder mig av *protanopia*-filtret för att testa färgblindheten. Det innebär att bilderna med olika färger förmedlar inte så mycket färger som man vill i det färgblinda läget självfallet, men det är en begränsning man får jobba med. Eftersom det jag vill förmedla med färger och kreativitetet borde ändå kunna komma fram i bland annat bilden med rollers där man verkligen förstår att det är olika färger som webbutvecklaren kan använda sig av. I övrigt är kontrasterna tillräckligt tydliga och inget särskilt sticker ut som svårt att se eller förstå när man jämför färgblindfiltret.  

<section class="ss-style-doublediagonal-index"></section>

<div class="sb sb-home">
      <small></small>
      <hr class="section-break-3" />
</div>


## UPPDRAG 4: Tema alternativt

## Arbete och implementation

Istället för att jobba mot markdown-filer i <code>{{ content }}</code> inuti twig-filerna valde jag att göra en if-sats mot vilket tema som är valt. När det vanliga temat är valt så laddas <code>{{ content}}</code>, dvs markdown-filerna, medan om det alternativa är valt genom månen längst nere så laddas inte markdown-filerna utan HTML-kod direkt inuti <code>"main"-diven</code>, dvs sidans innehåll. Då tappade jag tyvärr smidigheten som finns markdown-filerna men det var det enda lösningen jag hittade för att separera de olika temans HTML- och CSS-kod.


## Färgpaletten och valda färger.

På samma sätt med första temat använde jag mig av Adobes färgsnurra och en existerande hemsida för inspiration - Monclers hemsida. Temat blev en typ av dark mode men som passade kravet och hade därför egna designprinciper och skiljde sig markant från det första temat. 

För att välja färgpaletten tog jag en bild på Monclers startsida och matade in i Adobes "extrahera tema" (finns tillgänglig på sidan för Adobes färgsnurra) och fick ut flera färger jag gillade. Här valde jag inte att mata in den för att skapa någon färgharmoni utan jag använda dessa färger direkt från Monclers hemsida för att passa in på min sida. Jag la till några till toner av den mörka färgen för att komplettera mer. Om jag skulle försöka hitta en färgharmoni för mina färger skulle jag säga att den rör mot monokromt med en touch av en mer stylish färg i form av dena röda. Den hittade jag på första bilden jag matade in i "extrahera temat" och var en färg jag gillade väldigt mycket. Till en början hade jag den för knappar som var särskilt viktiga på hemsidan såsom att "contact me" och liknande men den fall bort i tillgängligheten för Google Lighthouse när den inte hade tillräcklig kontrast mot bakgrunden vilket var synd men inget jag kunde göra något åt.

<p><strong>Färgpalett</strong></p>
<table style="border-spacing: 4px; border-collapse: separate">
<tr>
<td style="height: 50px; width: 50px; border: 1px #fff solid; background-color: #0D0D0D">
</td><td style="height: 50px; width: 50px; background-color: #000">
</td><td style="height: 50px; width: 50px; background-color: #1A1A1A">
</td><td style="height: 50px; width: 50px; background-color: #6d6d6d">
</td><td style="height: 50px; width: 50px; background-color: #BFBFBF">
</td><td style="height: 50px; width: 50px; background-color: #E5E5E5">
</td><td style="height: 50px; width: 50px; background-color: #fff">
</td><td style="height: 50px; width: 50px; background-color: #ed0000">
</td></tr>
</table>

## Typografin, designprinciper och designelement

**Typografi**

Jag valde en serif-font för rubriker - **Playfair** som jag hittade på Google fonts hemsida som jag gillade. Den sticker ut mer och passar enligt mig för rubriker. För brödtext använde jag mig av **Roboto** som jag gillar. Det är sans serif-font jag tycker ser bra ut och passade det mörka temat samt är enkelt att läsa.

**Designprinciper**

*Rörelse*

Jag har använt mig av rörelse för navigationsfältet med två linjer som går in för att ge hemsidan lite liv samt vid projekten så vid <code>hover</code> så förstoras bildas. Det ger hemsidan ett mer livligt och häftigt intryck vilket är något jag försöker förmedla även med färgerna. 

*Kontrast* 

Eftersom jag använder en mörk färg och har vit font blir det tydliga kontraster. I övrigt på grund av det mörka temat så finns det inte lika mycket kontraster. På alla bilder har jag lagt <code>filter: greyscale(40%)</code> för att bilderna inte ska sticka ut alltför mycket utan naturligt smälta in med sidan. 

Jag testade även att använda mig av cimages <code>&convolve=darken</code> istället för att använda greyscale på flashbilden.


*Inraming*, *linjer* och *styrning*

På home-sidan har jag börjat med att först visa mina projekt för att den potentiella kunden ska få en snabb anblick på vilka typ av projekt jag gjort och förstå mina kunskaper. Sedan har jag som nästa element använt avskiljare (linjer) för att göra det enklare att överblicka och separera sektion. I nästa sektion har jag centrerat texten i ett ensamt stycke för att en introduction av mig är en viktig del för en potentiell kund. Här har jag både använt mig av styckets flera designprinciper för att få kunden att kolla hitåt för att det är viktig information som jag vill förmedla till kunden. 

*Hierarki*

Jag har inte jobbat mycket direkt med hierarkier men indirekt blir det alltid att man jobbar med det. T.ex. när man använder sig av en h1 och sedan en h2 så har man en underordnad hierarki som kan vara en textbox. Sedan har jag använt mig av header, content och en footer vilket kan vara en typ av hierarkistruktur.

*Negativt utrymme*

Med större utrymme och mer negativt utrymme mellan de olika html-elementen blir det både enklare att överblicka. Jag skulle säga att denna designprincip även löper in i linjer-principen där det handlar om att göra det läsbart och bryta av element mot varandra för att enklare se. Jag skulle säga att det är ganska mycket negativt utrymme på alla mina tre sidor och det är för att det inte ska se rörigt ut och att viktig information som jag vill förmedla ska vara enkel att hitta. Hade jag haft element överallt och inget negativt utrymme hade det varit svårt för mig att få den potentiella kundens uppmärksamhet.

*Balans*

På mina tre sidor har jag försökt hitta väga upp element till höger och vänster för att få en mer behaglig översikt. T.ex. på förstasidan längst nere har jag text till vänster och en bild till höger för att hela utrymmet ska användas och inte lämna alltför mycket negativt utrymme.


*Repetition*

För att koppla ihop flera individuella element har jag använt mig av en röd färg. Den syns när man <code>:hover</code> element och markeras vilken sida man är inne på i navigationsfältet. Det är en liten touch som jag gillar och som gör att hemsidan för en egen stylish touch som både sticker ut och igenkännande. jag hade gärna velat ha den på vissa element för att det är särskilt viktiga. T.ex. "Contact me by mail"-länken men det funkade inte kontrastmässigt enligt Lighthouse. 

På samma sätt med den röda färgern har jag försökt vara konsekvent med knapparna som har en svart vit ram runtom sig och är väldigt enkel i sin design men som tydlig visar att det är en knapp.


*Skala* och *grid*

På min highlights-sidan gjorde jag om min tidigare grid som var symmetriskt med rundande kanter till att istället vara en typ av grid-masonry. Det är något jag hade sett på hemsidor tidigare och var sugen att testa på. Så på highlights-sidan har jag celler som är olika långa då jag använt mig av <code>grid-row-end: span x</code> för att förlänga dem. Jag blev nöjd med resultatet och det ser lite mer raffinerat ut jämfört med om griden hade varit helt symmetrisk. På grund av masonry så kan man säga att jag använt mig av olika skalor då cellerna är av olika storlek.

## Känsla med det alternativa temat

Jag har som ovanstående information klargjort använt mig av en typ av mörkt tema men som även skiljer sig markant med designprinciper från det vanliga temat. Jag hittade inspirationen mycket ifrån Monclers hemsida. Moncler är ett lyxvarumärke och deras hemsida ska osa lyx och premiumkänsla och det tycker jag att de uppnår. Det gör de med hjälp av mycket svarta färger och en häftig typografi. Så det jag ville uppnå med temat är att få potentiella kunder att få en wow-känsla och känna att jag vill ha en liknande webbplats för locka dennes kunder. På så sätt kompletterar det vanliga temat som är mer ordinärt och minimalistiskt jämfört med detta tema som är mer bombastiskt och sticker ut mer tycker jag. Dvs. Jerry når ut till flera kundgrupper som den kan tänka sig att anställa honom.

Jag har likt det vanliga temat försökt att accentuera viktig information såsom erfarenhet och kontakt till honom genom inramning och liknande designprinciper för att det ska vara enkelt för användarna att hitta denna viktiga information.

## SASS

När jag började arbeta med SASS-koden för mitt alternativa tema och gjorde jag en kopia på respektive modul. T.ex. about-modulen - about.scss -> about-dark.scss. Sedan sparade jag den sass-koden jag kunde återanvända eller kommenterade bort den. Sen i samband med att jag utvecklade about-sidan så la jag antingen till ny SASS-kod, använde mig av den bortkommenterade koden eller tog inspiration från dessa för att skapa ny.

Genom att återanvända gammal kod eller ta inspiration ifrån kunde jag snabbare utveckla mina nya sidor. Jag har på samma sätt jobbat med att bryta ut sidor till egna moduler och i min "style-dark.scss" har jag gjort nya variabler med nya färger som jag sedan kan applicera på all text i hela sidan med hjälp av asterisk.


## Responsivitet och tillgänglighet

*Responsivitet*

Responsiviteten har jag arbetat med på samma sätt för det vanliga temat. Här använder jag mig av <code>grid-column: span x</code> och ändrar antal kolumner till ett så att innehållet centreras och kan rymma på den mindre skärmen. Jag gjorde även om lite i footern så att det skulle se lite bättre och passa in mer med kontaktinfo och ikonerna. Nu är ikonerna på vertikalen istället för horisontellt vid mobilt användande.  

*Tillgänglighet*

Tillgänglighet är 100% på samma sätt som första temat.



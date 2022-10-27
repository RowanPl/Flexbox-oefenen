# Opdrachtomschrijving
Zoals je hebt geleerd kun je met flexbox `HTML elementen` op diverse manier uitlijnen, maar ook complexe layouts maken. In de eerste opdracht ga je vooral de children (flex items) binnen de parent (flex container) uitlijnen. In het tweede deel ga je complexe layouts bouwen.

De `HTML elementen` (de containers en items) die je moet uitlijnen zijn al voor je klaargezet in de `index.html`. Benieuwd welke flexbox properties er allemaal zijn? Je vindt hier een overzicht van alle [Flexbox properties](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) uitgesplitst op properties die van toepassing zijn op de parent (flex container) en de children (flex items).

## Inhoudsopgave
### Opdracht 1: Positioneren met Flexbox
1. [Eindresultaat](#11-eindresultaat)
2. [Randvoorwaarden](#12-randvoorwaarden)
3. [Stappenplan](#13-stappenplan)
### Opdracht 2: Layouts bouwen met Flexbox
1. [Eindresultaat](#21-eindresultaat)
2. [Randvoorwaarden](#22-randvoorwaarden)
3. [Stappenplan](#23-stappenplan)

## Opdracht 1: Positioneren met Flexbox
### 1.1 Eindresultaat 

![Het eindresultaat op desktop](deel-1-flexbox-positioneren/assets/examples/voorbeeld-pagina-desktop.png)

### 1.2 Randvoorwaarden
In het `index.html` bestand hebben we 5 opdrachten uitgewerkt. Zorg ervoor dat deze onderdelen er exact zo uit komen te zien als in het voorbeeld dat erboven wordt weergegeven. De CSS voeg je toe aan het [styles.css](deel-1-flexbox-positioneren/styles/styles.css) bestand.

* Je hoeft géén nieuwe `HTML elementen` te creëren, maar daar waar nodig mag je wel classes toevoegen aan de bestaande elementen in het [index.html](deel-1-flexbox-positioneren/index.html) bestand;
* Elke deel-opdracht heeft een eigen `section` element. Dit element is om een nieuwe deel-opdracht aan te duiden en gebruik je niet om je elementen op uit te lijnen. Dit doe je dus alleen op de `div`, `ul` of `li` items;
* Je mag de bestanden (`.css` & `.html`) niet verplaatsen;
* Je mag het bestand `do-not-edit` niet aanpassen. Hier zit de basis-opmaak in voor de elementen;
* Je gebruikt enkel flexbox properties om de elementen uit te lijnen, dus geen `position`, `padding` of `margin`!

### 1.3 Stappenplan
Vind je het lastig om te beginnen? Volg dan het stappenplan.

_TIP_: Kom je er niet helemaal uit? Check of de parent container is voorzien van de benodigde flexbox properties en voeg telkens 1 nieuwe property toe en kijk of dit je een stap dichter bij het eindresultaat brengt. Voeg daarna pas een volgende property toe indien nodig.

#### Deelopdracht 1:
![Het resultaat van opdracht 1](deel-1-flexbox-positioneren/assets/images/opdracht-1-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Welke property heb je nodig om elementen evenredig over de gekozen hoofdrichting te verspreiden? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!

#### Deelopdracht 2:
![Het resultaat van opdracht 2](deel-1-flexbox-positioneren/assets/images/opdracht-2-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Zorg dat alle items dezelfde basis-breedte krijgen. Tip: gebruik hiervoor de `flex-basis`-property;

#### Deelopdracht 3:
![Het resultaat van opdracht 3](deel-1-flexbox-positioneren/assets/images/opdracht-3-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: in dit geval zou zowel `row` als `column` mogelijk zijn, maar wij hebben het met een `row`-richting gedaan!
- [ ] Zorg dat ieder item zichzelf op de juiste hoogte zet met de `align-self`-property. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-align-self) eens!

#### Deelopdracht 4:
![Het resultaat van opdracht 4](deel-1-flexbox-positioneren/assets/images/opdracht-4-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Zorg ervoor dat de elementen netjes binnen de container blijven staan, door ze naar de volgende regel te duwen wanneer ze niet meer passen. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flex-wrap) eens!
- [ ] Zorg ervoor dat alle elementen in de container 10 pixels van elkaar af staan. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!

#### Deelopdracht 5:
![Het resultaat van opdracht 5](deel-1-flexbox-positioneren/assets/images/opdracht-5-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Welke property heb je nodig om elementen evenredig over de gekozen hoofdrichting te verspreiden? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!
- [ ] Nu is het tijd om naar de items te gaan kijken. Hoewel zij flex-items zijn, zullen ze op hun beurt ook weer moeten fungeren als flex-container... Geef hen eerst een rode rand, zodat je duidelijk ziet wat je doet. 
- Zorg ervoor dat alle kolommen met de rode rand zich gedragen als een flex-container;
- [ ] Hoe krijg je de elementen die erin staan vervolgens weer onder elkaar (`column`)?
- [ ] In de kolommen loopt de hoofd-as van boven naar beneden. Welke property had je ook alweer nodig om items over de hoofd-as te verplaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!
- [ ] Als je goed oplet, zie je dat de items in de eerste kolom links uitgelijnd zijn, de items in de tweede kolom in het midden en de items in de rechter kolom rechts. Dit zul je dus voor iedere kolom apart moeten instellen. In de kolommen loopt de kruis-as van links naar rechts. Welke property had je ook alweer nodig om items over de kruis-as te verplaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-align-items) eens!

## Opdracht 2: Layouts met Flexbox

### 2.1 Eindresultaat
Alle afbeeldingen (maar wel verkleind!)

### 2.2 Randvoorwaarden
In iedere opdracht-map vind je een HTML-pagina met elementen en een (leeg) CSS-bestand. Zorg er met Flexbox voor dat de elementen zich precies zo positioneren als in het voorbeeld. Controleer hierbij ook altijd goed of de layout niet kapot gaat wanneer je de tekst eruit haalt, of juist meer tekst toevoegt.

* Je mag niets aanpassen in de `index.html` bestanden, maar daar waar nodig mag je wel classes toevoegen aan de bestaande elementen.
* Je mag het bestand `global-styles.css` niet aanpassen. Hier zit de basis-opmaak in voor de layouts, waaronder de achtergrond kleuren van de verschillende elementen.
* Je gebruikt enkel flexbox properties om de elementen uit te lijnen, dus geen `position`, `padding` of `margin`!

_TIP_: Als je `flex-shrink` of `flex-grow` properties wil gebruiken, zul je altijd eerst een `flex-basis`-waarde moeten declareren. Hoeft het element geen specifieke breedte te hebben, maar vooral alle overgebleven ruimte opvullen? Gebruik dan `flex-basis: auto` en wijs de juiste shrink- en grow-waardes toe.

### 2.3 Stappenplan
Vind je het lastig om te beginnen? Volg dan het stappenplan.

_TIP_: Kom je er niet helemaal uit? Teken eerst uit welke richtingen je allemaal nodig hebt om alle items naast- en onder elkaar te krijgen.

### Deelopdracht 1:
![Het resultaat van opdracht 1](deel-2-flexbox-layout/assets/images/opdracht-1-eindresultaat.jpg)

- [ ] Zorg dat de `body` zich gaat gedragen als een flex-container.
- [ ] Hoe krijg je de elementen die erin staan vervolgens weer onder elkaar (`column`)?
- [ ] Bij een kolommen loopt de hoofd-as van boven naar beneden. Welke property had je ook alweer nodig om items over de hoofd-as te verplaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens onder de flex-container properties (de licht paarse vlakken)!!
- [ ] Geef de body een minimale hoogte met de totale viewport height van je browser. Tip: bekijk edHub hoofdstuk 6. Simpele stijlregels > Eenheden nog eens!
- [ ] Als het goed is zie je nu alle elementen onder elkaar in een kolom. Welk element moet een rij vormen, zodat de hoofd-as van richting veranderd en de children (flex items) van dat element van links naar rechts lopen (`row`)? Ps: het klopt dat de volgorde van je `nav` en `aside` nog niet overeenkomt met het voorbeeld. Dit passen we later aan.
- [ ] Nu we de `body` en de `main` van flexbox properties hebben voorzien, kunnen we de children (flex items) gaan voorzien van flexbox properties.
- [ ] Geef alle flex-items (children van een flex-container) een `flex-basis` property en geef deze afhankelijk van de richting van de hoofd-as een waarde mee. Voor elementen die een horizontale hoofd-as hebben, kun je het best de viewport eenheid gebruiken en voor de verticale hoofd-as is dit meestal in pixels. Voor elementen die geen vaste hoogte/breedte hebben (zoals vaak bij het `main` element het geval is), mag je deze op `auto` zetten.
- [ ] Gebruik de `flex-grow` en flex-`shrink` properties om ervoor te zorgen dat de `header` en `footer` niet groeien of krimpen.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `main`, `nav`, en `aside` wel mogen groeien, maar niet krimpen.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `article` zowel kan groeien als krimpen.
- [ ] Als laatste zullen we de volgorde van de verschillende elementen moeten aanpassen. Weet je nog welke property je hiervoor op de flex-items moet plaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens onder de flex-items properties (de licht oranje vlakken)!
- [ ] Controleer of de layout nog steeds goed vertoond als je bijvoorbeeld 500 worden toevoegt aan het artikel. Tip: type `lorem500` en dan `tab` om een placeholder tekst van 500 worden te genereren

### Deelopdracht 2:
![Het resultaat van opdracht 2](deel-2-flexbox-layout/assets/images/opdracht-2-eindresultaat.jpg)
- [ ] Zorg dat de `body` zich gaat gedragen als een flex-container.
- [ ] De elementen zullen zich direct positioneren over de horizontale hoofd-as (dit is de default property). Toch is het goed om deze te specificeren (`row`)?
- [ ] Geef de body een minimale hoogte met de totale viewport height van je browser.
- [ ] Zorg dat de `div` en de `main` zich ook als een flex-container gaan gedragen en geef deze een richting mee zodat de elementen zich onder elkaar positioneren (`column`)?
- [ ] Geef alle flex-items (children van een flex-container) een `flex-basis` property en geef deze afhankelijk van de richting van de hoofd-as een waarde mee. Voor elementen die een horizontale hoofd-as hebben, kun je het best de viewport eenheid gebruiken en voor de verticale hoofd-as is dit meestal in pixels. Voor elementen die geen vaste hoogte/breedte hebben (zoals vaak bij het `main` element het geval is), mag je deze op `auto` zetten.
- [ ] Om er voor te zorgen dat het `article` element net zo groot wordt als de container, ook als er geen content in staat, moet deze een width property krijgen die de totale breedte inneemt van de container.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `nav`, `header` en `footer` niet groeien of krimpen.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `div` en de `main` zowel mogen groeien als krimpen.
- [ ] Controleer of de layout nog steeds goed vertoond als je bijvoorbeeld 500 worden toevoegt aan het artikel. Tip: type `lorem500` en dan `tab` om een placeholder tekst van 500 worden te genereren

### Deelopdracht 3:
![Het resultaat van opdracht 3](deel-2-flexbox-layout/assets/images/opdracht-3-eindresultaat.jpg)
- [ ] Zoals je kunt zien lijkt de opmaak van deze opdracht veel op de vorige. Lukt het je om de layout zonder hulp te kunnen maken? Spiek zo nodig eens bij de vorige opdracht.
- [ ] Om de flex-items in de `main` na hebben zij dezelfde de `flex-grow` en `flex-shrink` properties. 
- [ ] De `aside` mag niet groeien en krimpen.
- [ ] De article mag zowel groeien als krimpen.
- [ ] Controleer of de layout nog steeds goed vertoond als je bijvoorbeeld 500 worden toevoegt aan het artikel. Tip: type `lorem500` en dan `tab` om een placeholder tekst van 500 worden te genereren

### Deelopdracht 4:
![Het resultaat van opdracht 4](deel-2-flexbox-layout/assets/images/opdracht-4-eindresultaat.jpg)
- [ ] Zoals je kunt zien wordt de layout al wat complexer. Bekijk eerst goed welke delen van de pagina in de HTML-structuur zijn genest. 
- [ ] Zorg dat de `body` zich gaat gedragen als een flex-container.
- [ ] De elementen zullen zich direct positioneren over de horizontale hoofd-as (dit is de default property). Toch is het goed om deze te specificeren (`row`)?
- [ ] Geef de body een minimale hoogte met de totale viewport height van je browser.
- [ ] Zorg dat alle overige parent elementen zich ook gedragen als een flex-container.
- [ ] Zorg dat alle flex-containers een richting krijgen waarover de hoofd-as moet lopen. Teken dit zo nodig voor jezelf uit.
- [ ] Geef alle flex-items (children van een flex-container) een `flex-basis` property en geef deze afhankelijk van de richting van de hoofd-as een waarde mee. Voor elementen die een horizontale hoofd-as hebben, kun je het best de viewport eenheid gebruiken en voor de verticale hoofd-as is dit meestal in pixels. Voor elementen die geen vaste hoogte/breedte hebben (zoals vaak bij het `main` element het geval is), mag je deze op `auto` zetten.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `nav`, `header`, `aside` en de `footer` niet groeien of krimpen.
- [ ] Alle overige flex-items mogen zowel groeien als krimpen.
- [ ] Controleer of de layout nog steeds goed vertoond als je bijvoorbeeld 500 worden toevoegt aan het artikel. Tip: type `lorem500` en dan `tab` om een placeholder tekst van 500 worden te genereren

### Deelopdracht 5:
![Het resultaat van opdracht 5](deel-2-flexbox-layout/assets/images/opdracht-5-eindresultaat.jpg)
- [ ] Zorg dat de `body` zich gaat gedragen als een flex-container.
- [ ] De elementen zullen zich direct positioneren over de verticale hoofd-as (`column`)?
- [ ] Geef de body een minimale hoogte met de totale viewport height van je browser.
- [ ] Zorg dat het andere parent elementen zich ook gedraagt als een flex-container.
- [ ] Zorg dat deze flex-containers de richting krijgt waarover de hoofd-as moet lopen (`row`).
- [ ] Geef alle flex-items (children van een flex-container) een `flex-basis` property en geef deze afhankelijk van de richting van de hoofd-as een waarde mee. Voor elementen die een horizontale hoofd-as hebben, kun je het best de viewport eenheid gebruiken en voor de verticale hoofd-as is dit meestal in pixels. Voor elementen die geen vaste hoogte/breedte hebben (zoals vaak bij het `main` element het geval is), mag je deze op `auto` zetten.
- [ ] Gebruik de `flex-grow` en `flex-shrink` properties om ervoor te zorgen dat de `nav`, `header`, `aside` en de `footer` niet groeien of krimpen.
- [ ] Alle overige flex-items mogen zowel groeien als krimpen.
- [ ] Controleer of de layout nog steeds goed vertoond als je bijvoorbeeld 500 worden toevoegt aan het artikel. Tip: type `lorem500` en dan `tab` om een placeholder tekst van 500 worden te genereren




# Opdrachtomschrijving
Zoals je hebt geleerd kun je met flexbox `HTML elementen` op diverse manier uitlijnen, maar ook complexe layouts maken. In de eerste opdracht ga je vooral de children (flex items) binnen de parent (flex container) uitlijnen. In het tweede deel ga je complexe layouts bouwen.

De `HTML elementen` (de containers en items) die je moet uitlijnen zijn al voor je klaargezet in de `index.html`. Benieuwd welke flexbox properties er allemaal zijn? Je vindt hier een overzicht van alle [Flexbox properties](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) uitgesplitst op properties die van toepassing zijn op de parent (flex container) en de children (flex items).

## Inhoudsopgave
### Opdracht 1: Positioneren met Flexbox
1. Eindresultaat
2. Randvoorwaarden
3. Stappenplan
### Opdracht 2: Layouts bouwen met Flexbox
1. Eindresultaat
2. Randvoorwaarden
3. Stappenplan

## Opdracht 1: Positioneren met Flexbox
### Eindresultaat

![Het eindresultaat op desktop](flexbox-positioneren/assets/examples/voorbeeld-pagina-desktop.png)

### Randvoorwaarden
In het `index.html` bestand hebben we 5 opdrachten uitgewerkt. Zorg ervoor dat deze onderdelen er exact zo uit komen te zien als in het voorbeeld dat erboven wordt weergegeven. De CSS voeg je toe aan het [styles.css](flexbox-positioneren/styles/styles.css) bestand.

* Je hoeft géén nieuwe `HTML elementen` te creëren, maar daar waar nodig mag je wel classes toevoegen aan de bestaande elementen in het [index.html](flexbox-positioneren/index.html) bestand;
* Elke deel-opdracht heeft een eigen `section` element. Dit element is om een nieuwe deel-opdracht aan te duiden en gebruik je niet om je elementen op uit te lijnen. Dit doe je dus alleen op de `div`, `ul` of `li` items;
* Je mag de bestanden (`.css` & `.html`) niet verplaatsen;
* Je mag het bestand `do-not-edit` niet aanpassen. Hier zit de basis-opmaak in voor de elementen;
* Je gebruikt enkel flexbox properties om de elementen uit te lijnen, dus geen `position`, `padding` of `margin`!

### Stappenplan
Vind je het lastig om te beginnen? Volg dan het stappenplan.

_TIP_: Kom je er niet helemaal uit? Check of de parent container is voorzien van de benodigde flexbox properties en voeg telkens 1 nieuwe property toe en kijk of dit je een stap dichter bij het eindresultaat brengt. Voeg daarna pas een volgende property toe indien nodig.

### Deelopdracht 1:
![Het resultaat van opdracht 1](flexbox-positioneren/assets/images/opdracht-1-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Welke property heb je nodig om elementen evenredig over de gekozen hoofdrichting te verspreiden? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!

### Deelopdracht 2:
![Het resultaat van opdracht 2](flexbox-positioneren/assets/images/opdracht-2-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Zorg dat alle items dezelfde basis-breedte krijgen. Tip: gebruik hiervoor de `flex-basis`-property;

#### Deelopdracht 3:
![Het resultaat van opdracht 3](flexbox-positioneren/assets/images/opdracht-3-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: in dit geval zou zowel `row` als `column` mogelijk zijn, maar wij hebben het met een `row`-richting gedaan!
- [ ] Zorg dat ieder item zichzelf op de juiste hoogte zet met de `align-self`-property. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-align-self) eens!

#### Deelopdracht 4:
![Het resultaat van opdracht 4](flexbox-positioneren/assets/images/opdracht-4-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Zorg ervoor dat de elementen netjes binnen de container blijven staan, door ze naar de volgende regel te duwen wanneer ze niet meer passen. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flex-wrap) eens!
- [ ] Zorg ervoor dat alle elementen in de container 10 pixels van elkaar af staan. Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!

#### Deelopdracht 5:
![Het resultaat van opdracht 5](flexbox-positioneren/assets/images/opdracht-5-eindresultaat.jpg)
- [ ] Zorg dat het buitenste element zich gaat gedragen als een flex-container;
- [ ] Kijk naar de opbouw van de HTML-elementen en kies de hoofdrichting: moeten de elementen zich onder elkaar (`row`) of naast elkaar (`column`) bevinden?
- [ ] Welke property heb je nodig om elementen evenredig over de gekozen hoofdrichting te verspreiden? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!
- [ ] Nu is het tijd om naar de items te gaan kijken. Hoewel zij flex-items zijn, zullen ze op hun beurt ook weer moeten fungeren als flex-container... Geef hen eerst een rode rand, zodat je duidelijk ziet wat je doet. 
- Zorg ervoor dat alle kolommen met de rode rand zich gedragen als een flex-container;
- [ ] Hoe krijg je de elementen die erin staan vervolgens weer onder elkaar (`column`)?
- [ ] In de kolommen loopt de hoofd-as van boven naar beneden. Welke property had je ook alweer nodig om items over de hoofd-as te verplaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-justify-content) eens!
- [ ] Als je goed oplet zie je dat de items in de eerste kolom links uitgelijnd zijn, de items in de tweede kolom in het midden en de items in de rechter kolom rechts. Dit zul je dus voor iedere kolom apart moeten instellen. In de kolommen loopt de kruis-as van links naar rechts. Welke property had je ook alweer nodig om items over de kruis-as te verplaatsen? Tip: spiek [hier](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-align-items) eens!

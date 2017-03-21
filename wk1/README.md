# Opdracht 1.1

## Features
- JavaScript
- Kleur

## Mogelijke problemen

### Web apps vallen in het water
Google Drive onbruikbaar zonder JS
Google Drive is eerdere een software tool dan een website. Zonder JavaScript is deze echter niet bruikbaar. Volgens de schrijver maakt dat echter weinig uit, aangezien het een software tool is.
~ http://tobyho.com/2010/03/11/how-much-of-the-web-actually/

### Inloggen en comments plaatsen breekt af
Door het uitschakelen van JavaScript is de kans aanwezig dat het niet mogelijk is om in te loggen of comments te plaatsen.
~ https://www.howtogeek.com/138865/htg-explains-should-you-disable-javascript/

### Overweging JS library met Designer
Het overwegen van de toepasbaarheid van een JavaScript library is afhankelijk of de web designer het aanvaard dat zijn design slechts werkt als JavaScript ingeschakeld is.
~ http://tobyho.com/2010/03/11/how-much-of-the-web-actually/

## Hoe te testen?
- JavaScript kun je uitschakelen door in de browser JavaScript niet toe te staan.
- Chrome heeft een extensie ‘Colorblinding’ waarmee getest kan worden hoe kleurenblinden de website ervaren.

## Website uit directe omgeving met problemen

### JavaScript
#### Voetbalzone: 
login werkt niet, essentieel om in te loggen met mee te kunnen praten over voetbal; de slogan van de website.
tab onder ‘wedstrijden werkt niet’

#### NOS:
‘Topstories’ stort in: Teksten lopen over elkaar heen.
Sliders werken niet optimaal, werk bruikbaar.
Zoekfunctie werkt niet.
Tab rond nieuws categorieën werkt niet. 

### Kleur
Voetbalzone: 
Focus niet zichtbaar.
Hover button te subtiel

#### NOS:
Hover niets zichtbaar

## Hoe dit op te lossen
### Kleur
- De contrast ratio verhogen.
- De focus ook stijlen, desnoods zelfde styling hover-state


# Opdracht 1.2

## Progressive Enhancement Funda App

### 1. Afbeeldingen
Bij aanvang van dit onderzoek zijn de afbeeldingen uitgezet via de instellingen van de browser. Wat direct opviel is dat de afbeeldingen geen alt-attribuut hebben meegekregen, waardoor je niet kunt zien om wat voor afbeelding het oorspronkelijk ging.

#### Verbeterpunten
Voor screen readers is een invulde alt-attribuut natuurlijk zéér gewenst. Daarnaast is het van belang dat de naam van de website ten allen tijde zichtbaar is, tekstueel of visueel.

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/afbeeldingen.png?raw=true)


### 2. Custom fonts
De custom fonts, in dit geval Google Webfonts, zijn uitgeschakeld. Doordat achter de font-family-naam ‘sans-serif’ staat, vult de browser het ontbrekende font aan met een sans-serif-font.

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/fontstyle.png?raw=true)

###3 Verbeterpunten
Deze stack kan echter veel specifieker, zodat je nog de controle behoudt op de vertoning van de fonts die het dichtst in de buurt van de meest gewenste font komt. Met slechts sans-serif als fallback geef je de controle uit handen.


### 3. JavaScript
De Funda app is volledig onbruikbaar zonder JavaScript. De inhoud van de app wordt middels een API, aangeroepen in JavaScript, binnengehaald. Hierdoor is het niet mogelijk om de inhoud te tonen.


### 4. Kleur
Met behulp van de tool Sim Daltonism wordt getest hoe kleurblinden de website zien. Volgens het programma zijn de contrasten goed zichtbaar.

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/kleuren.png?raw=true)

#### Verbeterpunten
De hover-states zijn te subtiel vormgeven. Kleurenblinden zien hierdoor het verschil niet altijd tussen een hover-state en een normale state. Het is dan ook zaak om die hover-state prominenter te vertonen.


### 5. Muis/trackpad
Er is gebruik gemaakt van semantische HTML, met betekenisvolle HTML-tags als `input`, `a` en `select`. Bovendien zijn alle hover- en focus-states gestyled. Daarmee is de app met gemak te besturen met het toetsenbord en bovendien toegankelijk.

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/muistrack.png?raw=true)

### 6. Cookies
De app maakt geen gebruik van cookies.

#### Tools:
- Sim Daltonism
- Contrast Ratio Checker (Google Chrome extensie)
- Google Chrome Dev Tool

#### Getest in:
- Google Chrome versie 56
- Firefox 46.0.1

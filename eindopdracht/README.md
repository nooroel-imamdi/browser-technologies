# JavaScript
In deze stap van de opbouw wordt de techniek toegepast met behulp van JavaScript. Hiermee wordt de interactie van de website uitgebreid met nieuwe features.

## User case
Een aantal user cases zijn van te voren aangeboden door de docenten van dit vak. De user case die ik zal uitwerken luidt als volgt: ‘Ik wil boodschappen-om-tostis-te-maken in mijn boodschappenlijstje kunnen gooien’.

## Aanpak
Als eerste werd de volgende vraag beantwoord: wat gebeurd er een gebruiker geen JavaScript heeft? We hebben hiervoor de CSS toegepast die al bestendig was om zich te laten vallen voor statische bruikbare HTML. Om te checken of er JavaScript beschikbaar, wordt in de `head` van de HTML het volgende scriptje in geladen:

`<noscript>
	  <meta http-equiv="refresh" content="0; URL=index-nojs.html">
	</noscript>`

Hiermee wordt aangegeven dat de pagina `index-no-js.html` ingeladen zal worden, zodra de browser weet dat de gebruiker van de website geen JavaScript-ondersteuning kent. In dat geval wordt de gebruiker doorwezen naar een pagina met slechts HTML en CSS.


## Features

### Item toevoegen
Met behulp van JavaScript is het mogelijk om een item toe te voegen. Hierbij wordt met `appendChild` voor de gebruiker de weg vrijgemaakt om het boodschappenlijstje uit te breiden.


### Item doorhalen
Met behulp van een `toggle`-functie binnen JavaScript, kan de gebruiker items doorhalen. Het functioneert als het afvinken van items, bijvoorbeeld als de gebruiker een recept heeft weten te bemachtigen. 

### Item verbergen
Door specifieke classes aan te spreken bij het aanklikken van sluit-icon, is het mogelijk met JavaScript items te verbergen in het lijstje.


## Browser

### Internet Explorer 8
Op Internet Explorer werkt deze variant naar behoren. Het enige wat niet kan is het verwijderen en doorhalen van items. Wel is het mogelijk om het invoerveld en te vullen en deze item vervolgens toe te voegen aan de lijst.

In de volgende browsers werd deze pagina met succes getest:

Google Chrome
Firefox
Safari

### Accessibility
De checkboxes en button zijn bereikbaar bij het gebruik van de toetsenbord. De gebruiker is dus niet afhankelijk van de computermuis.
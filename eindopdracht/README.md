# CSS
In deze branche is de volgende stap gezet in de opbouw: het toepassen van CSS, oftewel ‘de presentatie’ van de website.

## User case
Een aantal user cases zijn van te voren aangeboden door de docenten van dit vak. De user case die ik zal uitwerken luidt als volgt: ‘Ik wil boodschappen-om-tostis-te-maken in mijn boodschappenlijstje kunnen gooien’.

## Aanpak
De css wordt opgebouwd met de hedendaagse technieken van CSS. Doordat niet alle browsers technieken als, bijvoorbeeld em’s, ondersteunen, wordt er een fallback met pixels aangemaakt. Hiermee wordt de waarde ook zichtbaar voor oude browsers.

## Features

### Flexbox & @Support
In deze opbouw van mijn CSS heb ik ervoor gekozen `Flexbox` en `@Support ` in combinatie te gebruiken. Reden hiervoor is dat de ondersteunen van deze twee technieken vrijwel gepaard gaat. 

#### Fallback
Om dit werkend te krijgen wordt er instantie nog gebruikt gemaakt van de oudere technieken, zoals `margin: 0 auto`. 

### EM to pixel
Niet alle browsers ondersteunen de eenheid `em`. Daarom is er op elke regel waar em is toegepast ook gebruik gemaakt van pixels, met de wetenschap dat 1em gelijk staat aan 16px.

## Browsers

Internet Explorer 8
In Internet Explorer lijkt veel niet te werken van de CSS. Enige zaken die vertoond worden zijn de background-color van de achtergrond en tot bepaalde een grens wordt de structuur van de pagina visueel nog getoond. De basisstructuur is uiteraard wel beschikbaar, waardoor het gewoon mogelijk is om je lijstje bij te houden en de website dus gewoon functioneert.

In de volgende browsers werd deze pagina met succes getest:

- Google Chrome
- Firefox
- Safari

## Accessibility
De checkboxes en button zijn bereikbaar bij het gebruik van de toetsenbord. De gebruiker is dus niet afhankelijk van de computermuis.
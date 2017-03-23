# Feature detectie

## HTML

### Datalist
Het HTML-element `<datalist>` bevat een reeks `<option>` elementen waarnaar verwezen kan worden middels een ID in een input-veld. Er vindt dus een koppeling plaats tussen de input-veld en de `<datalist>`. Bij het intypen van bijv. een zoekopdracht worden suggesties getoond.

- https://developer.mozilla.org/nl/docs/Web/HTML/Element/datalist
- https://davidwalsh.name/datalist


#### Ondersteunende browsers

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/wk2/caniuse-datalist.png?raw=true)

#### Fallback
Indien het `<datalist>` element niet ondersteund wordt, dan is het nog altijd mogelijk om het input-veld in te vullen. De essentie, namelijk het invoeren van informatie, blijft gehandhaafd. De ‘luxe’ suggesties ontbreken slechts.


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/html/datalist.html



### Details
De HTML `<details>` element wordt gebruikt als beschrijving-widget waaruit de gebruiker aanvullende informatie kan ophalen door middel van een klik of tab.

- http://www.hongkiat.com/blog/html5-details-summary-tags/
- https://developer.mozilla.org/nl/docs/Web/HTML/Element/details


#### Ondersteunende browsers

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/wk2/caniuse-details.png?raw=true)


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/html/details.html



## CSS

### Using CSS variables
CSS variabelen zijn entiteiten die worden gedefinieerd door de developer die de CSS schrijft. Met behulp van CSS variabelen kun je dezelfde waarden hergebruiken in de code. Doordat deze waarde op slechts een plek is aangegeven, namelijk bij het definiëren van de variabel, is het hierdoor mogelijk om met één aanpassing meerdere plekken tegelijk in de code te veranderen. Hierdoor hoef je niet meer dezelfde code handmatig aan te passen.

- https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables
- https://css-tricks.com/difference-between-types-of-css-variables/


#### Ondersteunende browsers

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/wk2/caniuse-cssvar.png?raw=true)


#### Fallback
De fallback van CSS variables is het ‘dubbel’ definiëren van een CSS-regel, namelijk de reguliere notatie en de notatie met de css variabel.

Voorbeeld:
`background-color: #4257B2;
background-color: var(—primair-color);`


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/css/variables.html



### @Support
De `@supports` gaat op dezelfde manier te werk als de `@media’ queries. Er kan een basis eigenschap met een waarde gecheckt worden om na te trekken of een bepaalde browser een bepaalde techniek binnen CSS ondersteund. In dat het geval is wordt de code binnen ‘@supports` uitgevoerd. Anders wordt de default toegepast die elders in de code is opgenomen.

- http://www.creativebloq.com/css3/how-use-supports-rule-your-css-11410545
- https://davidwalsh.name/css-supports


#### Ondersteunende browsers

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/wk2/caniuse-supports.png?raw=true)


#### Fallback
Indien `@supports` niet wordt ondersteund, dan valt deze terug op eigenschappen en waarden die wel worden ondersteund. De fallback is dan dat er in CSS regels worden geschreven die door oudere browsers ondersteund worden, zodat in gevallen dat `@supports` niet wordt ondersteund daarop terug kan worden gevallen.


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/css/supports.html


## JavaScript

### Dropdown menu
Het dropdown-menu verschijnt zodra de gebruiker op de menu-knop klikt of tapt. Deze techniek wordt veel gebruikt voor mobiele weergaves van websites. Deze techniek wordt veelal toegepast met JavaScript. 

- https://minor-everything-web.slack.com/files/jasper_voorhoede/F4N4UUYEA/2017-03-theme-parks-for-the-web.key


#### Fallback
Indien JavaScript niet wordt ondersteund, dan wordt er teruggevallen op de :target-hack van CSS. Hierdoor kan de gebruiker alsnog op de menu-knop klikken/tappen met hetzelfde resultaat. Verschil is alleen dat je op de close-knop moet klikken/tappen in plaats van het menu-knop om het dropdown-menu te sluiten.

![alt tag](https://github.com/nooroel-imamdi/browser-technologies/blob/master/wk2/caniuse-target.png?raw=true)


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/js/menu.html


#### Smooth scrolling
Met behulp van smooth scrolling kan de gebruiker met JavaScript op een soepele manier van de ene target naar de andere target binnen dezelfde pagina. Het geeft de gebruiker het gevoel dat hij ergens vloeiend naar toe wordt geleid.

- https://css-tricks.com/snippets/jquery/smooth-scrolling/
- http://codepen.io/chriscoyier/pen/dpBMVP


#### Fallback
De fallback is de reguliere manier van het volgen van targets, namelijk dat de gebruiker direct na het punt wordt geleid, zonder enige vertraging. Hierdoor blijft het bruikbaar.


Live demo: - https://cdn.rawgit.com/nooroel-imamdi/browser-technologies/master/wk2/js/smoothscrolling.html
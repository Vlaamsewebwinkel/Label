# Label Vlaamsewebwinkel
Integreer een label op jouw webwinkel van Vlaamsewebwinkel

# Wat is Vlaamsewebwinkel?
Vlaamsewebwinkel is een plaats waar alle vlaamse online winkels zich kunnen op aanmelden. Om de Vlaamse online verkoop te helpen stijgen. Met de label die wij aanbieden willen wij niet alleen de de kopers verzamelen. Maar willen wij ook de klanten van de webwinkels voldoende informatie geven over de webwinkel.

# Hoe integreer ik zo'n label op mijn website.
- Eerst maak je een account aan op onze website.
  Je kan kiezen tussen een gratis, solidair of premium account.
- Geef vervolgens enkele gegevens op van jouw webwinkel.
- Wij controleren deze gegevens.
- Als het is goedgekeurd kan kan je jouw label op jouw webwinkel plaatsen.

# CDN gebruiken
Sneller Vlaamsewebwinkel inladen?
Gebruik dan onderstaande link om vlaamsewebwinkel.js in te laden.
https://cdn.jsdelivr.net/gh/Vlaamsewebwinkel/Label@0.9.2.5/vlaamsewebwinkel.min.js

# Code

html
```html
<div id="vlaamsewebwinkellabel"></div>
```
```html
<script src="./jquery.js" charset="utf-8"></script>
```
```html
<script src="./vlaamsewebwinkel.min.js" charset="utf-8"></script>
```
****

javascript
```javascript
$( document ).ready(function() {
  var vww = new VWW("websitenaam","vlaamsewebwinkellabel","1","id");
  vww.createlabel();
});
```

# Waarbij de functie VWW volgende elementen bevat
* Websitenaam ter controle
* De naam van het element
* Ontwerp nummer van label dat je gekozen hebt.
* plaats je het in een html element met class of id

Je kan meerdere labels op één pagina plaatsen en ook verschillende id's of classen gebruiken hiervoor.

# Label Vlaamsewebwinkel
Integreer een label op jouw webshop van Vlaamsewebwinkel

# Wat is Vlaamsewebwinkel?
Vlaamsewebwinkel is een plaats waar alle vlaamse online winkels zich kunnen op aanmelden. Om de Vlaamse online verkoop te helpen stijgen. Met de label die wij aanbieden willen wij niet alleen de de kopers verzamelen. Maar willen wij ook de klanten van de webwinkels voldoende informatie geven over de webwinkel.

# Hoe integreer ik zo'n label op mijn website.
- Eerst maak je een account aan op onze website.
  Je kan kiezen tussen een gratis, solidair of premium account.
- Geef vervolgens enkele gegevens op van jouw webshop.
- Wij controleren deze gegevens.
- Als het is goedgekeurd kan kan je jouw label op jouw webshop plaatsen.

# CDN gebruiken


# Code

html
```html
<div id="vlaamsewebshoplabel"></div>
```
```html
<script src="./jquery.js" charset="utf-8"></script>
```
```html
<script src="./vlaamsewebshop.min.js" charset="utf-8"></script>
```

****

javascript
```javascript
$( document ).ready(function() {
  var vww = new VWW("1234567890","vlaamsewebshoplabel","1","id");
  vww.createlabel();
});
```

Waarbij de functie VWW volgende elementen bevat
* Website ID ter controle
* De naam van het element
* Ontwerp nummer van label dat je gekozen hebt.
* plaats je het in een html element met class of id

Je kan meerdere labels op één pagina plaatsen en ook verschillende id's of classen gebruiken hiervoor.

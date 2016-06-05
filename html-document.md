# Opbouw van een HTML-document

Een HTML-document is een tekstbestand ("platte tekst") met een bepaalde structuur. "Platte tekst" betekent dat je een HTML-bestand met elke teksteditor zoals Notepad kunt bewerken. Je hebt geen speciale tekstverwerker nodig. Vaak gebruik je hiervoor eenzelfde programma als waarmee je ook programmatekst bewerkt.

> Een tekstbestand bestaat uit UTF-tekens: letters, cijfers, leestekens, en speciale symbolen. Door het gebruik van UTF kun je ook tekens uit allerlei soorten schrift gebruiken. In de meeste gevallen beperken we ons tot de Ascii-tekens: dit zijn ongeveer de tekens die op je toetsenbord voorkomen.

De logische structuur van het document, zoals de browser dit ziet, bestaat uit elementen met een bepaalde betekenis.

Een paar voorbeelden van elementen:

```html
<h1>Dit is een titel</h1>

<p>
  Dit is tekst in een paragraaf. 
  Een enkel woord krijgt <em>nadruk</em>.
</p>
```

Een html-element bestaat uit een "openingshaakje", de inhoud van het document, en het bijbehorend "sluithaakje". In de voorbeelden hiervoor zijn `<h1>`, `<p>`, en `<em>` de openingshaakjes.

Door het gebruik van deze haakjesstructuur kun je elementen binnen elementen plaatsen. We spreken dan over *nesting*. Zo is in het voorbeeld het em-element genest binnen het p-element.

### HTML5

Een HTML-document begint met het `doctype` element. Dit geeft aan dat het een html-document is, en welke versie van html gebruikt wordt.

Het element `<!doctype html>` geeft aan dat je met een HTML-5 document te maken hebt. Deze versie van HTML wordt voortdurend uitgebreid en vernieuwd. Enkele zaken die nu deel uitmaken van HTML-5:

* ondersteuning voor media-bestanden: audio, video, graphics


### Evergreen browsers

Moderne browsers zijn "evergreen": deze worden regelmatig automatisch bijgewerkt naar een nieuwe versie. De gebruiker hoeft niet steeds een nieuwe versie te installeren; soms is het nodig om de browser opnieuw op te starten.




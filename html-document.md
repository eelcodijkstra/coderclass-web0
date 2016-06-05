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

### HTML-5

Een HTML-document begint met het `DOCTYPE` element. Dit geeft aan dat het een html-document is, en welke versie van html gebruikt wordt.

Het element `<!DOCTYPE html>` geeft aan dat je met een HTML-5 document te maken hebt. Deze versie van HTML wordt voortdurend uitgebreid en vernieuwd. Enkele zaken die nu deel uitmaken van HTML-5:

* ondersteuning voor media-bestanden: audio, video, graphics


### Evergreen browsers

Moderne browsers zijn "evergreen": deze worden regelmatig automatisch bijgewerkt naar een nieuwe versie. De gebruiker hoeft niet steeds een nieuwe versie te installeren; soms is het nodig om de browser opnieuw op te starten.


### Het verschil tussen HTML en PDF

Met een tekstverwerker maak je een document dat een vaste vorm heeft: op papier en op het scherm ziet dat er altijd hetzelfde uit.  Dit geldt ook voor een PDF-document: dit beschrijft precies de vorm zoals je die op het scherm of op het papier krijgt.

> Je kunt een PDF-document vergroten of verkleinen: de verdeling van de inhoud blijft altijd gelijk. De tekst wordt op dezelfde manier over de regels verdeeld, de figuren staan altijd op dezelfde plaats, enzovoorts.

In het geval van HTML past de browser de vorm aan, aan de omgeving waarin de inhoud getoond wordt. Als je het venster van de browser smaller maakt, wordt de inhoud anders verdeeld over het venster. Als je hetzelfde HTML-document bekijkt op een mobiel apparaat kan dit er behoorlijk anders uitzien dan wanneer je dit op een laptop of op een desktop-computer bekijkt. Als gebruiker heb je zo veel invloed op de vorm.

> Als gebruiker heb je veel invloed op de uiteindelijke vorm; je kunt bijvoorbeeld het lettertype aanpassen. Dit kan bijvoorbeeld handig zijn als je moeite met lezen hebt.

In het geval van PDF kun je spreken van een vaste vorm, in het geval van HTML van een "vloeibare" vorm. Deze wordt pas vastgelegd op het allerlaatste moment, in de omgeving van de gebruiker.

Dit stelt speciale eisen aan het ontwerp van HTML-pagina's: je moet ervoor zorgen dat deze in verschillende omstandigheden er behoorlijk uitziet.

> Begrippen die je tegenkomt zijn bijvoorbeeld" "mobile first" en "responsive design".




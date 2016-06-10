## Opdrachten hoofdstuk 1

### Hoe geef je de browser de webpagina door?

Zoek een onderwerp op Wikipedia, bijvoorbeeld het begrip "protocol". Welke stappen neem je daarbij, in welke volgorde?

* hoe kom je bij Wikipedia?
* hoe kom je bij het onderwerp, in Wikipedia?

Je kunt bijvoorbeeld gebruik maken van:

* een bookmark;
* het zoekveld van de browser;
* het adresveld van de browser;
* het zoekveld in een zoekmachine;
* het zoekveld in Wikipedia
* andere?

### Andere opdrachten

* Ga na of de browser die je gebruikt een *evergreen browser* is.

### Vaste en vloeibare vormen

* Bekijk een PDF-document op verschillende apparaten, en op papier. Vergroot en verklein het venster, en bekijk wat dit tot gevolg heeft.
* Bekijk een HTML-document op verschillende apparaten, en op papier. Vergroot en verklein het venster, en bekijk wat dit tot gevolg heeft.
* Pas in de browser-voorkeuren de minimale grootte van de letters aan.
* Pas in de browser-voorkeuren de lettertypes aan die je bij voorkeur gebruikt voor de weergave van tekst.

Je kunt hiervoor ook de ontwikkelhulpmiddelen in de browser gebruiken. Daarmee kun je zien hoe een webpagina er op een andere apparaat uitziet.

### HTML-documenten

Met behulp van Mozilla [X-ray Goggles](https://goggles.mozilla.org/) kun je een HTML-document bekijken en de weergave ervan aanpassen. Je kunt zo je eigen versie van een webpagina maken.

1. installeer X-ray Goggles
2. oefen met het voorbeeld (Mozilla).

Probeer vervolgens een ingewikkelder voorbeeld, zoals:

* maak een aangepaste versie van de homepagina van de website van je school.

Je kunt met Goggles niet alleen de inhoud aanpassen, zoals de tekst en de figuren, maar ook de vormgeving.

Zoek in het voorbeeld-document (XXX) een voorbeeld van een link. Deze heeft de volgende vorm:

```html
<a href="http://infvo.com/coderclass">Metis Coderclass wiki</a>
```

Hierin is de tekst tussen `<a>` en `<\a>` de tekst van de link, en de tekens tussen quotes na de `href=` de URL van de link.

* verander met Goggles de tekst van een link
* verander met Goggles in URL van een link


### Het web, dat maak je zelf

Met [Mozilla Thimble](https://thimble.mozilla.org/nl/) kun je eenvoudig je eerste website maken. Het eenvoudigst is om met een bestaand voorbeeld te beginnen. Dat kun je "*remixen* tot je eigen versie.

### URLs en links

* voer een mail-URL in in het webadres-veld van de browser, bijvoorbeeld: `mailto: eelco@infvo.com`.
* voer een URL in met een foutieve domeinnaam. Welke melding krijg je, en waar komt die vandaan?
* voer een URL in met een juiste domeinnaam, maar met een fout in de padnaam. Welke melding krijg je, en waar komt die vandaan?

**Bookmark** Maak van een webpagina die je veel gebruikt een bookmark in de browser. Geef deze bookmark een korte, duidelijke naam. Neem deze bookmark op in de favorietenbalk of in de favorietenpagina ("Top Sites").

**Tekst voor links** Voor de onderstaande opdrachten kies je een geschikte webpagina, die je bewerkt met X-ray Goggles.

1. Maak een link in een pagina met een misleidende tekst - die de gebruiker van die link naar een heel andere URL stuurt dan deze verwacht.

2. Maak een link in een pagina met een duidelijke tekst - die de gebruiker een duidelijke aanwijzing geeft over de bestemming (URL) van die link.

### Protocollen - HTTP(S)

1. laad de onderstaande pagina in de browser, door op de link te klikken; en bekijk de interactie met de server in de ontwikkeltools.
2. ververs deze pagina (met de "ververs" knop van de browser), en bekijk de interactie met de server.
3. vul het formulier in, en stuur dit op naar de server ("Submit"). Bekijk de interactie met de server in de ontwikkeltools.
4. ververs deze pagina (met de "ververs" knop van de browser), en bekijk de interactie met de server.

Beschrijf in het kort de belangrijkste zaken die je hierbij opgevallen zijn.

### DNS; IP-adressen

Zoek op het web een dienst die via DNS het IP-adres van een domein kan vinden, en omgekeerd. Gebruik deze om het IP-adres van een domein dat je veel gebruikt te vinden.

* Wat is het IP-adres van het domein van je school?
* Wat is je eigen IP-adres als je via het schoolnetwerk het web bezoekt?
* Wat is het IP-adres van een andere leerling als deze via het schoolnetwerk het web bezoekt?

Voor gevorderden:

* Als je met meerdere gebruikers hetzelfde IP-adres lijkt te hebben, hoe kan de server dan deze gebruikers onderscheiden?
* Als je vanuit een browser eenzelfde server bezoekt, worden deze verschillende sessies meestal netjes uit elkaar gehouden; hoe kan de server dit doen? (Eventueel: met verschillende browsers.)

## Controlevragen

Uit welke delen bestaat een URL?

We gebruiken als voorbeeld-URL `http://infvo.com/basis/index.php?title=Hoofdpagina`. Geef hierin aan:

* de querystring
* het pad (de padnaam)
* het protocol (het schema)
* de domeinnaam

Geef een voorbeeld van een URL (in WikiPedia) met een fragment-identifier.

**URL-begrippen** Combineer de volgende voorbeelden aan hun soort:

* `192.168.1.255`
* `http:`
* `infvo.nl`
* `http://infvo.com/basis`


Gebruik de begrippen: IP-adres, schema (protocol), domeinnaam, URL, 

Waarom kun je een gewone pagina in de browser wel verversen, en een pagina met een formulier dat je opgestuurd hebt, niet? 

**HTTP-requests** Welke HTTP-opdracht (request) wordt gebruikt voor:

* het ophalen van een normale pagina
* het ophalen van een plaatje
* het opsturen van een ingevuld formulier

**idempotent** Welke van de volgende opdrachten zijn *idempotent*?

* geef de teller N de waarde 13
* hoog de teller N met 1 op
* reset de teller N naar de default-waarde

### Opmerkingen

Bij de meeste andere modules werken we, naast de eenvoudige opdrachten om iets te proberen of na te doen, met open opdrachten waarbij de leerlingen zelf iets kunnen maken.


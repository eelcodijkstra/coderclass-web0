# Links en URLs

Een URL (Uniform Resource Locator) is het *webadres* van een webpagina of van een web-app (web-toepassing).

Voorbeelden van URLs:

* `http://infvo.com/coderclass`
* `https://google.nl`
* `https://thimble.mozilla.org/nl/`

Een URL 

Een URL bestaat uit de volgende onderdelen:

* het protocol (`http:`, `https:`)
* de domeinnaam (`infvo.com`, `google.nl`, `thimble.mozilla.org`)
* de padnaam (`coderclass`, `nl/`)
* de querystring (`?x=a&y=b`)
* de hash(?)


Het *protocol* geeft aan op welke manier met de server gecommuniceerd moet worden. Voor webdocumenten is dit `http` of `https`. 

> Je kunt in een URL ook andere protocollen tegenkomen, bijvoorbeeld: `mailto:eelco@infvo.com`. Als je een dergelijke URL gebruikt in de browser, zal deze het mailprogramma opstarten met het gebruikte mailadres.

De *padnaam* beschrijft het pad naar de bewuste resource, in een hiërarchische structuur (een boom).

> Dit kun je vergelijken met de naam van een bestand op een computer. Op een Unix-systeem (Linux, OS X) heeft dit de vorm: `a/b/c`: ga eerst naar directory `a`, daarin naar directory `b`, en vind daarin bestand `c`.

### Relatieve URLs

We hebben tot nu toe absolute URLs besproken. Je kunt in een HTML-document ook *relatieve URLs* tegenkomen. Deze hebben de volgende vorm:

* het protocol en de domeinnaam ontbreken; het protocol en het domein van het huidige document wordt gebruikt;
* soms ontbreekt ook de padnaam; dan verwijst de link naar een positie in het huidige document.
* de padnaam is een relatief pad ten opzichte van het huidige document. Je kunt hierin ook onderdelen tegenkomen van de vorm `..`: hiermee ga je "1 stap hoger in het pad".

### Fouten in URLs

Je kunt een fout maken bij het intikken van een URL, of een document kan een link bevatten met een foute URL. Afhankelijk van het soort fout krijg je een verschillend gedrag:

* als de domeinnaam fout is, kan het DNS-systeem de server niet vinden; je krijgt dan een foutmelding van de browser.
    * soms krijg je een ander domein te zien dan je bedoeld had: er zijn de nodige domeinen aangemaakt voor het aantrekken van dit soort fouten.
* als de domeinnaam goed is, maar de padnaam fout, krijg je een "404" foutpagina van de server.

### Identificatie of adres?

Omdat een URL altijd verwijst naar dezelfde "resource", kun je deze ook gebruiken als *identificatie* (naam) van deze resource.

> Als het alleen gaat om de identificatie spreek je soms over *URI*: Uniform Resource Identifier.

> Een naam hoeft niet uniek te zijn: een resource kan onder verschillende namen (URLs) bekend zijn.
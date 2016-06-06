# Links en URLs

Een URL is het webadres van een webpagina of van een web-app (web-toepassing).

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

Je kunt in een URL ook andere protocollen tegenkomen, bijvoorbeeld: `mailto:eelco@infvo.com`. Als je een dergelijke URL gebruikt in de browser, zal deze het mailprogramma opstarten met het gebruikte mailadres.

### Fouten in URLs

Je kunt een fout maken bij het intikken van een URL, of een document kan een link bevatten met een foute URL. Afhankelijk van het soort fout krijg je een verschillend gedrag:

* als de domeinnaam fout is, kan het DNS-systeem de server niet vinden; je krijgt dan een foutmelding van de browser.
    * soms krijg je een ander domein te zien dan je bedoeld had: er zijn de nodige domeinen aangemaakt voor het aantrekken van dit soort fouten.
* als de domeinnaam goed is, maar de padnaam fout, krijg je een "404" foutpagina van de server.
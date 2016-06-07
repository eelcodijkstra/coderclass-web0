# Protocollen

Het *Hypertext Transfer Protocol* (HTTP) beschrijft de regels voor de communicatie tussen de browser en de server. Dankzij dit protocol weten de browser en de server steeds wie "aan zet" is, en wat er verwacht wordt.

*HTTPS* is de beveiligde variant van HTTP. HTTPS gebruikt dezelfde verzoeken (requests) als HTTP.

De belangrijkste soorten requests zijn:

* GET: verzoek aan de server om een web-document naar de browser te sturen, bijvoorbeeld een html-bestand.
* POST: versturen van gegevens van de browser naar de server, bijvoorbeeld de velden van een ingevuld formulier.

Voor een overzicht van de andere requests, zie: [Wikipedia: HTTP]( https://nl.wikipedia.org/wiki/Hypertext_Transfer_Protocol).

Een GET-request bevat onder andere de volgende gegevens:

* URL
* `Host`: hostnaam van de URL
* `User-Agent`: gegevens over de browser en het Operating System
* gebruikte HTTP-versie (bijv. `HTTP 1.1`)
* `Referer`: de URL van het document met de link gebruikt voor deze URL (de verwijzende pagina)
* `Accept`: het type resultaat dat de browser verwacht.
* `Cookies`: eventuele cookies van deze server die de browser opgeslagen heeft. 

In het antwoord stuurt de server ook extra gegevens op in de "headers":



Een POST-request bevat, naast de gegevens van een GET-request, onder andere de volgende gegevens:





# Protocollen

Het *Hypertext Transfer Protocol* (HTTP) beschrijft de regels voor de communicatie tussen de browser en de server. Dankzij dit protocol weten de browser en de server steeds wie "aan zet" is, en wat er verwacht wordt.

*HTTPS* is de beveiligde variant van HTTP. HTTPS gebruikt dezelfde verzoeken (requests) als HTTP.

De belangrijkste soorten requests zijn:

* GET: verzoek aan de server om een web-document naar de browser te sturen, bijvoorbeeld een html-bestand.
* POST: versturen van gegevens van de browser naar de server, bijvoorbeeld de velden van een ingevuld formulier.

Voor een overzicht van de andere requests, zie: [Wikipedia: HTTP]( https://nl.wikipedia.org/wiki/Hypertext_Transfer_Protocol).

Een GET-opdracht bevat onder andere de volgende gegevens:

* URL
* `Host`: hostnaam van de URL
* `User-Agent`: gegevens over de browser en het Operating System
* gebruikte HTTP-versie (bijv. `HTTP 1.1`)
* `Referer`: de URL van het document met de link gebruikt voor deze URL (de verwijzende pagina)
* `Accept`: het type resultaat dat de browser verwacht.
* `Cookies`: eventuele cookies van deze server die de browser opgeslagen heeft. 

In het antwoord stuurt de server ook extra gegevens op in de "headers":

* QQQQ

Een POST-opdracht bevat, naast de gegevens van een GET-opdracht, onder andere de volgende gegevens:

* QQQQ

### GET is idempotent - POST niet

De GET-opdracht *idempotent*: het resultaat is hetzelfde als je dit één keer uitvoert, of vaker. Als je een pagina in de browser herlaadt via de "refresh" knop in de browser krijg je weer hetzelfde resultaat. 

De POST-opdracht is niet *idempotent*: als je een formulier opnieuw opstuurt, kan dit een extra effect hebben. Als het een bestelformulier is, kun je op die manier een product tweemaal bestellen. De browser waarschuwt daarom altijd in dit geval, met de vraag of je zeker weet dat je het formulier nog een keer wilt insturen.

### Stapelen van protocollen

HTTP gebruikt het TCP-protocol, wat op zich weer het IP-protocol gebruikt. Dit is het basisprotocol van het internet. In een WiFi netwerk gebruikt IP het WiFi-protocol voor de "fysische laag". Deze fysische laag zorgt voor het daadwerkelijke transport van de bits in deze verschillende protocollen. Op deze manier krijg je een stapel ("stack") van protocollen:




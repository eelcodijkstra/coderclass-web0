# Security (veiligheid)

Je gebruikt het web voor veel zaken - bijvoorbeeld voor winkelen, internetbankieren, maar ook gewoon voor zoeken en "surfen".
Voor winkelen en internetbankieren is de veiligheid vanzelfsprekend van belang: je wilt niet dat anderen je verkeer met de bank kunnen afluisteren, of nog erger: dat anderen je rekening kunnen raadplegen en misschien plunderen.

Ook voor het gebruik van zoekmachines en veel "eenvoudige" websites is veiligheid steeds belangrijker, bijvoorbeeld om voor voldoende privacy te zorgen.

> Het normale webverkeer kan afgeluisterd worden - en wordt ook steeds meer afgeluisterd. Dit is één van de redenenen waarom steeds meer websites het versleutelde https-protocol gebruiken.

Welke veiligheidsproblemen kun je tegenkomen bij het gebruik van het web?

* http-verkeer kan afgeluisterd worden. Dit geldt in het bijzonder voor het verkeer in een openbaar netwerk, zoals een WiFi netwerk in de trein of in een cafe.
* de server waarmee je denkt te communiceren kan een compleet andere server zijn: in het internet kun je niet eenvoudig zien met wie je te maken hebt.
* omgekeerd kan de server waarmee je communiceert ook niet eenvoudig controleren wie jij bent.

Voor veel diensten moet je wachtwoorden gebruiken. Soms lekken deze wachtwoorden uit: ze "komen op straat te liggen" of worden door een hacker gevonden.

### Identificatie en authenticatie

* identificatie: wie ben je?
* authenticatie: kun je bewijzen wie je bent?

De eenvoudigste en meest gebruikte vorm van authenticatie is de combinatie gebruikersnaam/wachtwoord.

Voor extra veiligheid worden soms extra stappen gebruikt: voor internetbankieren moet je een extra apparaatje gebruiken dat sleutels genereert, of je gebruikt een SMS-bericht voor een extra code.

* vingerafdrukken;
* andere biometrische gegevens.

### Certificaten

Hoe weet je met wie je te maken hebt, als gebruiker van een website of web-app? Is dit echt de website van de bank, of die van iemand anders die door de bank na te doen je gegevens wil achterhalen?

> Een voorbeeld van een dergelijke actie is de poging om in te breken bij de Nationale Onderzoeksraad. Hiervoor is een nep-website ingericht met als URL `https://onderzoekraad.nl`, compleet met certificaat: de bezoekers krijgen netjes het slotje te zien.

Waar moet je op letten in zo'n geval?

* een website met een https-verbinding heeft een certificaat: dit geeft de URL van de website, en de eigenaar van de website.
* een certificaat is alleen te vertrouwen als het door een instantie uitgegeven is die te vertrouwen is. 

Iedereen kan zelf een certificaat maken: een certificaat alleen maakt het niet veilig. Dit certificaat moet uitgegeven zijn door een instantie die te vertrouwen is.

> De browser controleert hier hier op: als je zelf een certificaat maakt, zullen de meeste browsers dat als niet-veilig aanmerken.

## Enkele voorbeelden van bedreigingen

We geven hieronder enkele voorbeelden van veiligheidsbedreigingen waar je als gebruiker van het internet mee te maken kunt krijgen. Vaak heb je te maken met een combinatie van deze technieken.

### Phishing

We spreken over *Phishing* als iemand op een slinkse manier probeert geheime gegevens, zoals wachtwoorden, te achterhalen. Als gebruiker kun je onder andere op de volgende manieren misleid worden:

* een misleidende URL: de link leidt je naar een andere plek dan je denkt;
     * de tekst van de link suggereert iets anders dan werkelijke verwijzing via de URL van de link;
     * de URL verschilt net een klein beetje van de bedoelde URL, bijvoorbeeld: onderzoekraad.nl in plaats van onderzoeksraad.nl (zie 


* http://www.risicosinbeeld.nl/homepage/Hoe_herken_je_phishing
* https://en.wikipedia.org/wiki/Phishing

### Man in the middle



### Over de veiligheid van de browser

In principe is een browser zo opgezet dat deze geen software (inclusief virussen) kan installeren zonder medeweten en medewerking van de gebruiker. Maar: software is niet perfect, en ook een browser kan veiligheidsgaten bevatten. Je kunt het risico van deze gaten wel sterk verkleinen:

* browser-plugins vormen het grootste risico: in het bijzonder Java (applets) en Flash vormen een risico. Schakel deze plugins niet in. Gebruik plugins alleen voor websites die je helemaal vertrouwt.
* een verouderde browser vormt ook een risico: zorg er daarom voor dat je de meest recente versie hebt. Moderne browsers zoals Chrome en Firefox zijn "evergreen browsers": deze werken zichzelf regelmatig bij. Je hebt dan niet alleen de grootste veiligheid, maar ook de meest moderne web-functionaliteit.




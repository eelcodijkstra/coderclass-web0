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


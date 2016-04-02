## APIs
En god blanding av norske API-er
(A) = Authentisering

##Reise

##Matbutikker
  - Rema
   - Søk på sted, postnummer eller butikknavn: [Søk på postnummer 1482](https://www.rema.no/api/v2/stores/search?q=1482)
  - Meny
   - (A) [Tilbuder i butikk](https://service-dk.norgesgruppen.no/api/Data/Promotions/1300?ResultScope=1&channel=app)
   - [Alle butikker](https://ng-azure-rest-api-prod.azurewebsites.net/api/FindStore/Stores/1300)
  - Kiwi
   - (A) Både nærmeste butikk og alle sammen: POST med authentisering og koordinater, [eksempel her](kiwi.md)

##Kiosker
- Narvesen
   - (A) [Alle butikker](http://rcno-narvesen2.feeds.barcodes.no/Stores/NX16AFBC6F36FE647F4BAE1C1FC82693404) [(eksempel fra 1.april2016)](navesen-kiosker1april2016.json)

##Offentlige API-er (som ikke er på Data Norge)
- Informasjon om bilen ved å slå opp reg.nummer. Eksempel med reg.nr [DL10000](http://www.vegvesen.no/System/mobilapi?registreringsnummer=DL10000)

##Bensinstasjoner
- UNO-X, [alle stasjoner i skandinavia](https://erhverv.unox.dk/poi/ds2.csv)

##Andre API-er
- Nye bysykkeler i Oslo 2016 fra ClearChannel
 - [Autentisere ved å sende tlf-nummer og motta sms.](https://oslobysykkel.no/api/v1/sessions) [eksempel på data](bysykkel-autentisering.md)
 - For å motta sesjons-ID som benyttes videre for authentisering, token sendes som del av URL https://oslobysykkel.no/api/v1/sessions/3253b80ba8648e72af32a9df5c4138fd (URL kun som eksempel, må endres)
 - [Antall ledige sykler på stativ](https://oslobysykkel.no/api/v1/stations/availability), ID matches mot eget oppslag
 - (A) Navn og posisjon på sykkelstativ: https://oslobysykkel.no/api/v1/stations (autentiserings eksempel på header: Authorization: Token token="82653350c509a33eaeb4e1d1c382b545194f4bc1a7983f1d2f179b993c4ef982") [liste over alle stasjoner 1april2016](bysykkel-stativer1april2016.json)

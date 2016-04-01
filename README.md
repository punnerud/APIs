## APIs
En god blanding av norske API-er
A = Authentisering

##Reise

##Matbutikker
  - Rema
   - Søk på sted, postnummer[1482] eller butikknavn: https://www.rema.no/api/v2/stores/search?q=1482
  - Meny
   - (A) Tilbud i butikk: https://service-dk.norgesgruppen.no/api/Data/Promotions/1300?ResultScope=1&channel=app
   - Alle butikker: https://ng-azure-rest-api-prod.azurewebsites.net/api/FindStore/Stores/1300
  - Kiwi
   - (A) Både nærmeste butikk og alle sammen: POST med authentisering og koordinater, [eksempel her](kiwi.txt)

##Kiosker
- Narvesen
   - (A) Alle butikker: http://rcno-narvesen2.feeds.barcodes.no/Stores/NX16AFBC6F36FE647F4BAE1C1FC82693404 [(alle kiosker 1.april2016)](navesen-kiosker1april2016.json)

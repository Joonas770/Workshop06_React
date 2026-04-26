# Workshop 06 React 
Tämä tehtävä on osa full-stack kurssia. Tehtävässä luodaan fullstack-blogi sovellus.

Tehtävä koostu kahdesta osasta
* Backend (Node.js + Express), joka tarjoaa REST-rajapinnan ja yhteys luotu MongoDB tietokantaan.
* Frontend(React), jolla luotu käyttöliittymä käyttäjälle.

MongoDB-tietokantaan tallennetaan blogipostaukset sekä Mongoosea käytetään datan validointiin ja skeemojen määrittelyyn.


# Toteutukset
- Luotu yhteys MongoDB-tietokantaan connectDatabase() funktiolla server.js tiedostossa sekä .env tiedosto, johon määritelty yhteys sekä portti.
- Post Schema tiedostoon lisätty kentät: title, content sekä author ja näille arvot määritelty.
- Tarkistettu postauksien lisäys, päivitys ja poistaminen onnistuneesti.
- Virheenkäsittely
- CORS-ongelma ratkaistu lisämäällä corssin server.js
- Postmania käytetty API pyyntöjen tarkastamiseen ja tietojen lisäämiseen ja poistamiseen.
- Luotu React-sovellus Vite:llä
- Toteutettu router reititys 
- Haettu data backendistä fetch-kutsuilla
- graaffinen toteutus postauksien listaukselle, lisäämiselle, poistamiselle ja muokkaamiselle.

# Käyttöönohje
1. Avaa terminaali ja siirry kansioihin starter/backend ja starter/frotend ja lataa paketit npm install.
2. Linkitä MongoDB database .env tiedostoon luo jos ei ole
3. Käynnistä molemmat frotend and backend localhostiin npm run dev komennolla
4. Avaa frotendin localhost ja lisää postauksiin dataa.


# Yhteenveto
Projektissa toteutettiin fullstack-blogisovellus Reactilla, Node.js:llä ja MongoDB:llä. Sovellus mahdollistaa postausten luomisen, hakemisen, muokkaamisen ja poistamisen (CRUD). Backend tarjoaa REST-rajapinnan ja huolehtii tietokannasta, kun taas frontend vastaa käyttöliittymästä ja kommunikoi backendin kanssa fetch-kutsuilla. Lopputuloksena syntyi toimiva fullstack-sovellus, jossa kaikki perustoiminnot toimivat end-to-end.
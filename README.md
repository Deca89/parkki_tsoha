# Parkki ohjelma

Ideana tehdä pohja koirapäiväkodin laskutuksen seurantaan.

Funktiot jaetaan kolmelle eri yksikölle

- Johtaja
    - kykenee lisäämään uusia käyttäjiä
    - kykenee tekemään yhteenvedon maksamattomista laskuista
    - kykenee tarkastelemaan käyntejä
    - kykenee merkkaamaan laskut maksetuiksi
    - kykenee myös tekemään työntekijän funktiot
- Työntekijä
    - kykenee ilmoittamaan päivän aikana hoidossa olleet koirat
    - kykenee liittämään erillisiä huomioita päivän aikana tapahtuneista kriittisistä asioista
- Asiakas
    - kykenee tarkastelemaan laskujaan (maksettuja ja maksamattomia)
    - näkee jäljellä olevien käyntikertojen määrän

Ohjelma toimii siis kirjautuneen käyttäjän oikeuksien mukaisesti.
Ohjelmaan liitetään yleiset funktiot (sisäänkirjautuminen, salasanan vaihto...)

Alustavat taulukot:
* Taulukko käyttäjistä (joihin ainoastaan asiakkaan sukunimi ja koiran nimi tietoturvan vuoksi - käyntikertojen määrä myös!)
* Taulukko maksamattomista laskuista (tämä tärkeä, nopea suoritus)
* Taulukko maksetuista laskuista (asiakkaiden yleistä katselua varten, nopeus ei niin kriittinen tekijä)
* Taulukko, johon voidaan tallettaa päivien koirat

Asiaan tehtävä vielä hieman tarkennuksia ja sovittava missä muodossa tiedonsyöttö / ulosotto.
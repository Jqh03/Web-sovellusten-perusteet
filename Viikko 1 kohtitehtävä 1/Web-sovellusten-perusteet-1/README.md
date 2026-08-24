# W1 Kotitehtävä — Etusivu-HTML

**Kurssi:** Web-sovellusten perusteet  
**Viikko:** 1  
**Deadline:** Katso Moodlesta

---

## Tehtävän kuvaus

Rakenna henkilökohtainen esittelysivu puhtaalla HTML:llä. Sivu ei käytä JavaScript-koodia — tarkoitus on harjoitella HTML:n semanttista rakennetta ja keskeisiä elementtejä.


## Tehtävät

Tehtävät löytyvät `index.html`-tiedostosta `<!-- TODO: -->` -kommentteina.

| # | Tehtävä | Mitä tehdään |
|---|---------|--------------|
| 1 | Sivun rakenne | Täytä header (oma nimi ja esittelylause) ja korjaa nav-linkit osoittamaan osioiden id-kohtiin |
| 2 | Tietoja minusta | Kirjoita vähintään kaksi kappaletta, kummassakin vähintään kaksi lausetta |
| 3 | Taidot-lista | Valitse ul tai ol ja listaa vähintään neljä taitoa |
| 4 | Taulukko | Viikon ohjelma: thead-otsikkorivi ja tbody, jossa vähintään kolme riviä ja kolme saraketta |
| 5 | Kuva | Poista kuva-osion kommentointi ja lisää kuva, jolla on kuvaava alt-teksti |
| 6 | Footer | Lisää tekijänoikeusteksti omalla nimelläsi ja vuosiluvulla |


## Ohjeet

1. Kloonaa repositorio.
2. Avaa `index.html` VS Codessa.
3. Löydä kaikki `<!-- TODO: -->` -kommentit ja täytä ne.
4. Avaa sivu selaimessa tarkistaaksesi, miltä se näyttää.
5. Kun olet valmis: `git add .`, `git commit -m "W1 kotitehtävä valmis"` ja `git push`.
6. Kuittaa GitHub-repositoriossa issue valmiiksi.

## Tarkista työsi koneellisesti

Repositoriossa on valmis validaattori. Aja se ennen palautusta:

```bash
npm install   # vain ensimmäisellä kerralla
npm test
```

Komento tarkistaa kaksi asiaa:

- `npm run test:html` — validoi `index.html` (html-validate)
- `npm run test:css` — validoi `css/`-kansion tyylitiedostot (stylelint)

Jos komento tulostaa `0 problems`, HTML on rakenteellisesti kunnossa. Huomaa, että validaattori tarkistaa vain HTML:n oikeellisuuden — se ei tarkista, oletko täyttänyt kaikkia TODO-kohtia tai kirjoittanut järkevää sisältöä. Starter-pohja antaa virheen `<h1> cannot be empty`, kunnes lisäät otsikkoon oman nimesi.

Vinkki: HTML tarkistetaan ensin, joten korjaa sen virheet ennen kuin CSS-tarkistus pääsee ajoon.

## Arviointikriteerit

**HTML:n oikeellisuus (tarkistetaan W3C-validaattorilla):**
- Ei validointivirheitä — tavoite
- 1–3 pientä varoitusta — hyväksytään
- Rakenteellisia virheitä — ei hyväksytä

**Semanttisuus:**
- Oikeat elementit oikeissa kohdissa (`article`, `section`, `nav`, `header`, `footer` eikä `div` kaikkeen)
- `table` sisältää `thead`- ja `tbody`-elementit
- `img`-elementillä on kuvaava `alt`-attribuutti
- `nav`-linkkien `href="#id"` osoittaa olemassa olevaan osioon

**Sisältö:**
- Kaikki TODO-kohdat täytetty

## Usein kysyttyä

**Saako käyttää AI-apuvälinettä?**  
Koodin ymmärtäminen on tärkeämpää kuin itse kirjoittaminen. Jos käytät apua, varmista, että pystyt selittämään jokaisen koodirivin merkityksen.

**Mitä jos sivu ei näytä hyvältä?**  
Ei haittaa. Harjoitus arvioidaan HTML:n rakenteen ja oikeellisuuden perusteella, ei visuaalisen ulkoasun.

**Mitä jos jokin elementti puuttuu valitsemastani aiheesta?**  
Voit käyttää keksittyä sisältöä. Tehtävän tarkoitus on HTML-rakenne, ei tietojen todenperäisyys.

---

*Kysymyksiä? Kysy tunnilla tai Moodlen keskustelukanavalla.*
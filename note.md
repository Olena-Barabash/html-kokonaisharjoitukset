Totta! Koska tehtävässä pitää näkyä kaikki aiemmin opitut taidot ja uutena aiheena attribuutit, kannattaa tehdä selkeä tapahtuman esittelykortti, jossa jokaiselle vaatimukselle on luonteva käyttötarkoitus.

Tässä valmis sisältöidea HTML-sivulle. Aiheena voisi olla esimerkiksi Helsinki Design Week.

Tapahtuman sisältö
Sivun otsikko

Helsinki Design Week 2026

Lyhyt esittely

Helsinki Design Week on vuosittainen muotoilutapahtuma, joka kokoaa yhteen suunnittelijoita, opiskelijoita, yrityksiä ja muotoilusta kiinnostuneita ihmisiä. Tapahtumassa voi tutustua uusiin ideoihin, näyttelyihin, keskusteluihin ja työpajoihin.

Tapahtuman tiedot
Päivämäärä: 3.–13. syyskuuta 2026
Paikka: Helsinki
Teema: Muotoilu ja tulevaisuus
Kenelle: Kaikille muotoilusta ja luovasta suunnittelusta kiinnostuneille
Ohjelma

Näyttelyt
Tutustu erilaisiin designnäyttelyihin ja suomalaisen muotoilun uusiin näkökulmiin.

Työpajat
Osallistu käytännön työpajoihin ja kokeile itse erilaisia suunnittelumenetelmiä.

Keskustelut
Kuuntele asiantuntijoita ja suunnittelijoita, jotka keskustelevat muotoilun tulevaisuudesta.

Kuva

Kuvan voisi olla esimerkiksi moderni design-esine tai Helsingin kaupunkimaisema.

Alt-teksti esimerkiksi:
Moderni suomalainen design-esine pöydällä Helsingin kaupunkimaiseman edessä

Figcaption:
Suomalainen muotoilu yhdistää käytännöllisyyden ja visuaalisuuden.

Navigaatio

Voit tehdä sivulle esimerkiksi nämä suhteelliset linkit:

Etusivu → index.html
Ohjelma → ohjelma.html
Yhteystiedot → yhteystiedot.html

Voit lisätä myös ulkoisen turvallisen linkin esimerkiksi tapahtuman viralliselle sivulle käyttäen target="_blank" ja rel="noopener noreferrer".

Attribuuttien käyttö

Näin saat kaikki tehtävässä vaaditut attribuutit näkyviin luonnollisesti:

id → tapahtuman pääkortille, esimerkiksi id="tapahtuma"
class → tyylittelyä varten, esimerkiksi class="event-card"
title → lisätietoa esimerkiksi painikkeeseen tai linkkiin
lang → esimerkiksi englanninkieliselle ilmaukselle lang="en"
data-* → tapahtuman lisätiedolle, esimerkiksi data-category="design"
alt → kuvan kuvaileva vaihtoehtoinen teksti
target="_blank" + rel="noopener noreferrer" → turvallinen ulkoinen linkki

Esimerkiksi tapahtuman kortissa voisi olla:

<article id="tapahtuma" class="event-card" data-category="design">
    <h1>Helsinki Design Week 2026</h1>

    <p>
        Helsinki Design Week kokoaa yhteen suunnittelijoita,
        opiskelijoita ja muotoilusta kiinnostuneita ihmisiä.
    </p>

    <figure>
        <img src="images/design.jpg"
             alt="Moderni suomalainen design-esine Helsingin kaupunkimaiseman edessä"
             title="Helsinki Design Week 2026">
        <figcaption>
            Suomalainen muotoilu yhdistää käytännöllisyyden ja visuaalisuuden.
        </figcaption>
    </figure>

    <h2>Tapahtuman tiedot</h2>

    <p>
        <strong>Päivämäärä:</strong> 3.–13. syyskuuta 2026<br>
        <strong>Paikka:</strong> Helsinki<br>
        <strong>Teema:</strong> <span lang="en">Design and Future</span>
    </p>

    <h2>Ohjelma</h2>

    <p>
        Tapahtumassa järjestetään näyttelyitä, työpajoja
        ja keskusteluja.
    </p>

    <a href="ohjelma.html" title="Katso tapahtuman ohjelma">
        Tutustu ohjelmaan
    </a>

    <p>
        <a href="https://www.helsinkidesignweek.com/"
           target="_blank"
           rel="noopener noreferrer"
           title="Helsinki Design Weekin virallinen verkkosivusto">
            Tapahtuman virallinen verkkosivusto
        </a>
    </p>
</article>


Tällä rakenteella saat samaan työhön näkyviin HTML-perustan, otsikot ja kappaleet, linkit, kuvan, figure/figcaptionin sekä kaikki tehtävässä mainitut attribuutit.
# VHL Group – julkiset sähköpostikuvat

Tämä repo jakaa julkisesti kuvat, joita VHL Groupin sähköpostiallekirjoitukset näyttävät. Sähköpostin
vastaanottaja lataa kuvat suoraan GitHubista, esimerkiksi
`https://raw.githubusercontent.com/Mora-VHL/vhl-public-assets/main/vhl-logo-email-300px.png`, joten
repon täytyy olla julkinen. Tänne ei laiteta mitään muuta kuin julkiseksi tarkoitettuja kuvia.

## Tärkein sääntö

**Käytössä olevaa tiedostoa ei saa poistaa, nimetä uudelleen eikä korvata eri sisällöllä.** Jokainen
allekirjoitus ja jokainen jo lähetetty sähköposti hakee kuvan tästä osoitteesta aina, kun viesti
avataan. Jos tiedosto katoaa, kuva katoaa kaikista allekirjoituksista ja vanhoista viesteistä.
Uusi versio lisätään uudella nimellä, ja vanha jätetään paikalleen.

## Tiedostot

| Tiedosto                     | Käyttö                                                                         |
| ---------------------------- | ------------------------------------------------------------------------------ |
| `vhl-logo-email-300px.png`   | Allekirjoituksen logo. Sama tiedosto kuin vanhassa jakelussa (ks. alla).       |
| `allekirjoitus-testi/`       | Animoidun allekirjoitusbannerin riskitesti (ei lopullinen ulkoasu).            |

## Tausta

Kuvia jaettiin aiemmin henkilökohtaisesta reposta `Sabata79/vhl-public-assets`, koska se oli
aikanaan ainoa tapa hostata kuva. Jakelu siirretään tänne VHL:n omalle tilille. **Vanhaa repoa ei
poisteta:** henkilöstön nykyiset allekirjoitukset ja lähetetyt viestit viittaavat siihen.
Uudet allekirjoitukset osoittavat tähän repoon.

Tuleva animoitu allekirjoitusbanneri, jonka vuodenaikatausta vaihtuu itsestään, tulee VHL Intran
omasta pilvipalvelusta. Tämä repo on käytössä logolle ja testeille siihen asti.

## Riskitesti (`allekirjoitus-testi/`)

Testaa, miten Outlook ja vastaanottajat käsittelevät kuvista koottua, animoitua allekirjoitusta:

1. Lataa `allekirjoitus-testi/riskitesti.html` koneelle ja avaa se selaimessa.
2. Kopioi testiallekirjoitus ja liitä se vanhan Outlookin, uuden Outlookin ja selain-Outlookin
   allekirjoitusasetuksiin.
3. Lähetä testiviesti Outlook-, Gmail- ja puhelinosoitteeseen.
4. Tarkista vastaanotetusta viestistä, onko kuva **linkki** tähän repoon vai **liite**. Vain
   linkkinä vuodenaika voi vaihtua itsestään. Tarkista myös, liikkuuko lumi, toimivatko
   sähköposti- ja verkkolinkit ja näkyvätkö alt-tekstit, jos kuvat on estetty.

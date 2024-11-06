# TehtäväSovellusArkki

## Keskeiset osat

- **HomeController.cs**: Sisältää `Product`-toiminnon, joka lukee `products.json`-tiedoston ja muuntaa sen `Product`-olioiksi.
- **products.json**: Tiedosto, joka sisältää tuotteiden tiedot JSON-muodossa, kuten nimi, hinta, kuvaus ja kuva.
- **Product.cs**: `Product`-malli sisältää tuotteen ominaisuudet, kuten nimen ja hinnan, ja tarjoaa myös `FormattedName` ja `FormattedPrice`-ominaisuudet.
- **Product.cshtml**: Razor View, joka renderöi tuoteluettelon selaimeen käyttämällä `Product`-mallia.

## Tiedonsiirron ja näkymien logiikka

1. **`HomeController` lukee `products.json`-tiedoston** ja deserialisoi sen `Product`-olioiksi.
2. **`Product.cshtml`-näkymä käyttää `Product`-tietoja** ja renderöi tuotteiden tiedot HTML-muotoon.
3. **`site.js`** ja **`site.css`** parantavat tuotteen näkymän muotoilua ja hintojen esitystapaa.

# Verkiezingsuitslagen

In deze GitHub repository is de code te vinden die verkiezingsdata op de kaart toont.
Deze pagina is te bereiken via https://hilbrand.github.io/verkiezingsuitslagen

## Gegevens

De gegevens die getoond worden zijn verzamelt uit de EML bestanden die door de kiesraad beschikbaar worden gesteld na een verkiezing.
Deze bestanden zijn ingelezen en in een PostgreSQL database gezet.
Hiervoor is gebruikt gemaakt van de bibliotheken: https://gitlab.com/nl-h72/eml-hulpmiddelen en https://gitlab.com/nl-h72/eml-sql.
De resultaten zijn geografisch gekoppeld met behulp van de lokaties van stembureaus die de Open State Foundation publiceert op https://waarismijnstemlokaal.nl
Deze informatie is aangevuld met de CBS wijken en buurten gegevens om de uitslagen per wijk te tonen.

### Disclaimer

Helaas zijn de locatiegevens per stembureau niet compleet waardoor het niet goed mogelijk is de precies juiste cijfers te tonen.
Er is zo goed mogelijk geprobeerd de gegevens te verwerken.

&copy Hilbrand Bouwkamp

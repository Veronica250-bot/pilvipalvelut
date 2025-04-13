viikko 2


## Jekyll-teema ja CI/CD 

Jekyll-sivustoa voi automatisoida helposti GitHub Actions -toiminnolla. GitHub Pages tukee Jekylliä suoraan, joten sivut rakennetaan automaattisesti aina kun muutoksia tehdään `main`-haaraan. Jos halutaan enemmän hallintaa, voidaan käyttää omaa workflow-tiedostoa `.github/workflows/`-kansiossa, jossa määritellään esimerkiksi testaukset ja ulkoasun tarkistukset ennen julkaisua.

Web-sovellusten CI/CD-putkiston rakentamiseen voidaan käyttää työkaluja kuten GitHub Actions, Travis CI tai GitLab CI. Kehitystyökaluihin kuuluu mm. ESLint, Prettier, Jekyll build testit, sekä mahdollisesti Cypress- tai Playwright-testit automaattiseen testaamiseen. Julkaisun voi automatisoida esimerkiksi Netlifyllä tai suoraan GitHub Pagesin kautta, jolloin sivu päivittyy aina uusimman version mukaan.

Näin varmistetaan sivuston toimivuus ja laadukas kehitysprosessi.

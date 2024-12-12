# Velkakartta

Tervetuloa TIEA207 Projektikurssin repositorioon!
----------------------------------------------------------------------------------------------------------------------
## Tekijät
- **Joakim Kaseva**
- **Olli Terävä**
- **Onni Huhtala**
- **Petri Hukkanen**
----------------------------------------------------------------------------------------------------------------------

### Asennusohjeet
1. Vedä viimeisimmät muutokset repositoriosta komennolla:
   `git pull`
2. Asenna tarvittavat riippuvuudet backend ja frontend kansioissa:
   `npm install`
3. Luo .env tiedosto, ja lisää seuraavat rivit:
   ```
   PORT=3001
   IMF_DEBT = 'https://www.imf.org/external/datamapper/api/v1/GGXWDG_NGDP'
   IMF_TOTAL_DEBT = 'https://www.imf.org/external/datamapper/api/v1/CG_DEBT_GDP'
   IMF_INDICATOR = 'https://www.imf.org/external/datamapper/api/v1/indicators'
   IMF_GDP = 'https://www.imf.org/external/datamapper/api/v1/NGDPD'
   IMF_POPULATION = 'https://www.imf.org/external/datamapper/api/v1/LP'
   IMF_GG_DEBT = 'https://www.imf.org/external/datamapper/api/v1/GG_DEBT_GDP'
   ```
4. Korjaa mahdolliset eslint viat:
   `npx eslint --fix .js_tiedoston_sijainti`
----------------------------------------------------------------------------------------------------------------------

### Paikallinen suoritus
3. Backendin käynnistäminen: Käynnistä backend paikallisesti komennolla:
   `npm start`
4. Frontendin käynnistäminen paikallisesti:
   `npm run dev`
----------------------------------------------------------------------------------------------------------------------

### Huomioitavaa
- Varmista, että käytät oikeita portteja molemmissa palvelimissa.
- Komentorivillä näkyy URL, jossa sovellus pyörii.
- Mikäli kohtaat ongelmia, tarkista ensin virheilmoitukset ja varmista, että kaikki riippuvuudet on asennettu oikein.
----------------------------------------------------------------------------------------------------------------------

### Deployattu versio
- Sovellus käynnistyy URL:n painettua, hetki menee sen latautuessa. 
- Deployattu versio löytyy [Renderistä](https://debtmap-2024.onrender.com/)
  

----------------------------------------------------------------------------------------------------------------------

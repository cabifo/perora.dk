# perora.dk

Den danske hjemmeside for Perora Press. Indtil videre en »Kommer snart«-side med logoet.

Den engelske side ligger i projektet [cabifo/perorapress.com](https://github.com/cabifo/perorapress.com).
GitHub kan kun knytte ét domæne til hvert projekt, derfor er der to.

Siden kører på GitHub Pages fra grenen `main` (mappen `/`). Domænet står i filen `CNAME`.
DNS hos simply.com: A- og AAAA-poster for `@` til GitHub Pages og en CNAME-post `www` → `cabifo.github.io`.

## Ændre teksten

Teksten står i `index.html`. Den samme side ligger i `404.html`, som vises på adresser, der ikke findes.

perorapress.dk viser den samme danske side fra projektet [cabifo/perorapress.dk](https://github.com/cabifo/perorapress.dk) — ret teksten begge steder.

## Filer

- `logo.svg`: det fulde logo (originalfilen, uændret)
- `favicon.svg`, `favicon.png`, `apple-touch-icon.png`: ikonet i browserfanen og på hjemmeskærmen
- `og-image.png`: billedet, der vises, når linket deles
- `fonts/`: skrifttypen Cinzel (SIL Open Font License, se `fonts/OFL.txt`)

# Začeti sestavlajti projekte s Create React App

Create React App je udobno okolje za učenje Reacta in najboljši način za začetek gradnje nove enostranske aplikacije v Reactu.

Skrbi za konfiguracijo vašega razvojnega okolja za uporabo najnovejših funkcij JavaScript, zagotavlja odlično razvojno izkušnjo in optimizira vašo aplikacijo za produkcijo. 

Preden ustvarimo nov React projekt, moramo namestiti program `npx`, (vgrajen v npm v5.2+), ki izvaja pakete:

`npm install -g npx`

V računalniku morate imeti nameščen `Node >= 14.0.0` in `npm >= 5.6`. Če želite ustvariti projekt, vtipkajte:

`npx create-react-app moja-app`

`cd moja-app`

`npm start`

## Skripti na razpolago

V imeniku projekta lahko vtipkajte:

### `npm start`

Aplikacijo zažene v razvojnem načinu.\
Odprite [http://localhost:3000](http://localhost:3000) in si jo oglejte v brskalniku.

Stran se bo ponovno naložila, ko boste izvedli spremembe.\
V konzoli lahko vidite tudi morebitne napake lint.

### `npm run build`

Zgradi aplikacijo za produkcijo v mapo `build`.\
Pravilno poveže React v produkcijskem načinu in optimizira gradnjo za najboljšo zmogljivost.

#### Namestitev

Zgradba je pomanjšana, imena datotek pa vključujejo hashe.\
Vaša aplikacija je pripravljena za namestitev!

Za več informacij glejte razdelek o [nameščanju](https://facebook.github.io/create-react-app/docs/deployment).

To poglavje se je preselilo sem: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` ne uspe pomanjšati

To poglavje je bilo premaknjeno sem: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
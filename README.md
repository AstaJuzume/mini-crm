# Mini CRM · Power Apps prototipas

Naršyklėje veikiantis interaktyvus Model-driven Power Apps stiliaus prototipas, parengtas pagal 2026-11-23 komercinį pasiūlymą.

## Funkcijos

- Klientų ir kontaktų kūrimas, peržiūra, redagavimas bei šalinimas; kontaktų susiejimas su klientais.
- Paieška, rodiniai, filtravimas pagal miestą ir veiklą, rikiavimas, puslapiavimas, žymėjimas ir CSV eksportas.
- Dinaminiai segmentai pagal miestą, veiklą, aktyvumą ir sutikimą.
- Naujienlaiškio vedlys: segmentas, Mailchimp šablonas, tema, peržiūra, juodraštis ir demonstracinis inicijavimas.
- Gavėjų atrankoje tikrinamas sutikimas, prenumerata ir kliento aktyvumas.
- RIVILĖ ir Mailchimp demonstracinė sinchronizacija, įrašų būsenos ir integracijų žurnalas.
- Vienodas vidinių naudotojų prieigos lygis; atskiros aplikacijos rolės neįtrauktos.

## Ribos

Tai statinis prototipas su pavyzdiniais duomenimis, išsaugomais `localStorage`. Tikros Power Apps, Dataverse, RIVILĖ ir Mailchimp paslaugos neprijungtos, laiškai nesiunčiami. Paskyrų teisių sistema ir licencijavimas neimituojami. Lietuvos įmonių importas pasiūlyme yra galimas atskiras etapas ir neįtrauktas.

## Paleidimas

Statinis pradinis failas: `index.html`. Pakanka bet kurio statinių failų serverio, aptarnaujančio repozitorijos pagrindinį aplanką. Priklausomybių ir build žingsnio nėra.

## Patikra

- `node --check app.js`.
- Naršyklėje patikrintas kliento kūrimas, išsaugojimas po perkrovimo ir paieška.
- Patikrintas segmento kūrimas bei gavėjų perskaičiavimas.
- Patikrintas šablono pasirinkimas, temos įvedimas, peržiūra ir demonstracinio inicijavimo rezultatas.
- Patikrinta sinchronizacija ir rezultatas integracijų žurnale.
- Patikrintas kontakto sutikimo reikalavimas ir išsaugojimas.

## GitHub Pages

Settings → Pages → Deploy from a branch → main → / (root).

Alternatyvi veikianti demonstracija: https://mini-crm-power-apps-demo.prodivi.chatgpt.site

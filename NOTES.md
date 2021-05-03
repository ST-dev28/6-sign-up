- [x] pradine failu struktura
   - index.html
   - .gitignore
- [x] paviesinti projekta per Github Pages (gausim URL)
- [x] README.md
   - skirta aprasyti, kas, ka ir kodel daro
   - iterpti nuoroda i daroma dizaina
   - iterpti nuoroda, kur tas musu kodas g.b. pamatytas
- [x] atlikti dizaino analize
- [x] surasyti HTML
- [x] isikirpti nuotaukas ir jas panaudoti (istatyti tinkamas reiksmes i HTML)
   - panaudoti reliatyvu kelia
   - PNG formatas (del permatomumo savybes)
- [x] aprasome stiliu: 
   - turinys turi buti centre (tiek vertikaliai, tiek vertikaliai)
   - pagrindinis plotis t.b. fiksuotas (pikseliais, ne procentais)
- [x] atskiri puslapiai, kurie naviguoja "ratu"
  - sign up
  - sign in
  - forgot password
- [x] css turi buti tik vienas failas, kur stiliaus taisykles veikia vienodai (identiskai) per visus puslapius

# Pozicionavimas

1. Vaikui duodam `position: absolute`
2. Artimiausiam logiskam teviniam elementui, kuri norim tureti kaip atskaitos taska, suteikiame:
   a) `position: relative`, jei tas elementas neturi kitu `position` savybiu;
   b) paliekame tokia `position` savybe, kokia tas elementas turi, jei nenurodytas;

   Isvada:
   absoliuciai pozicionuojamas elementas bus pastatytas artimiausio ne `position: static` atzvilgiu. 
   `postion: absolute` nera static !!!
cvut-oi-mssz cvut-oi-mssz [PDF](https://github.com/vlcekmi3/cvut-oi-mssz/blob/master/oi-magistr.pdf?raw=true)
-------------

* __témata__: [http://www.fel.cvut.cz/cz/education/master/topicsOI.html](http://www.fel.cvut.cz/cz/education/master/topicsOI.html)

### INFO & TIPS & CONVENTIONS
* `00-template` - složka obsahující šablonu pro tvorbu nové otázky
* generování PDF:
  * 2-3 běhy generování (kvůli správné indexaci křížových odkazů)
* commit message při změně/úpravě otázek:
```
spolecna/05/TAL
+ algoritmus
+ spravnost (variant, invariant)
```
* před commitem:
  * zkontrolovat zda neobsahuje nějaké temp soubory (případně je zahrnout do `.gitignore`)
  * přegenerovat výsledné PDF (aby repozitář vždy obsahoval aktuální PDF)

### FILES
* `reference.bib` - seznam veškeré literatury
* `/_lib/csplainnat.bst` - podpora českýho typu citací
* `/_lib/colors.sty` - vlastně definované barvy
* `/_lib/qtree.sty` - knihovna pro kreslení stromů [http://www.ling.upenn.edu/advice/latex/qtree/](http://www.ling.upenn.edu/advice/latex/qtree/)
* `/_lib/infodata.sty` - soubor s doplňujícími informacemi na úvodní stranu (nadpisy apod.)
* `/_lib/codestyle.sty` - soubor s doplňujícími příkazy pro výpisy kódu
  * definice barev pro klíčová slova kódu
  * SQL, HTML, Java, PHP
* `/_lib/mathstyle.sty` - soubor s doplňujícími příkazy pro matematické rovnice, matice apod.
* `/_lib/macros.sty` - soubor s dalšími doplňujícími příkazy)

### SPOLEČNÉ
01. `PAL` - Amortizovaná složitost. Prioritní fronty, haldy (binární, d-regulární, binomiální, Fibonacciho), operace nad nimi a jejich složitost.
02. `PAL` - Neorientované a orientované grafy, jejich reprezentace. Prohledávání grafu (do hloubky a do šířky), topologické uspořádání, souvislost, stromy, minimální kostra.
03. `PAL` - Lexikální analyzátor, syntaktický strom, syntaktický analyzátor shora dolů, LL(1) gramatiky, rozkladové tabulky.
04. `PAL` - Algoritmy vyhledávaní v textu s lineární a sublineární složitostí, (naivní, Boyer-Moore), využití konečných automatů pro přesné a přibližné hledání v textu.
05. `TAL` - Algoritmus, správnost algoritmu, složitost algoritmu, složitost úlohy, třída P, třída NP.
06. `TAL` - NP-úplné a NP-těžké úlohy, Cookeova věta, heuristiky na řešení NP-těžkých úloh, pravděpodobnostní algoritmy.
07. `TAL` - Turingovy stroje, rekurzivní a rekurzivně spočetné jazyky, algoritmicky neřešitelné úlohy.
08. `KO` - Metoda větví a mezí. Algoritmy pro celočíselné lineární programování. Formulace optimalizačních a rozhodovacích problémů pomocí celočíselného lineárního programování. Toky a řezy. Multi-komoditní toky.
09. `KO` - Nejkratší cesty. Úloha obchodního cestujícího. Heuristiky a aproximační algoritmy. Metoda dynamického programování. Problém batohu. Pseudo-polynomiální algoritmy.
10. `KO` - Rozvrhování na jednom procesoru a na paralelních procesorech. Rozvrhování projektu s časovými omezeními. Programování s omezujícími podmínkami.

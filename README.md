cvut-oi-mssz
-------------

* __témata__: [http://www.fel.cvut.cz/cz/education/master/topicsOI.html](http://www.fel.cvut.cz/cz/education/master/topicsOI.html)
* __PDF společné__: [https://github.com/vlcekmi3/cvut-oi-mssz/blob/master/spolecne/oi-magistr-spolecne.pdf](https://github.com/vlcekmi3/cvut-oi-mssz/blob/master/spolecne/oi-magistr-spolecne.pdf?raw=true)
* ..

### INFO & TIPS & CONVENTIONS
* `00-template` - složka obsahující šablonu pro tvorbu nové otázky
* k indentování používat 4 mezery (NE tabulátor)
* generování PDF:
  * 2-3 běhy generování (kvůli správné indexaci křížových odkazů)
* commit zprava:
```
[spolecna][05][TAL]:
+ algoritmus
+ spravnost (variant, invariant)
```
* před commitem:
  * zkontrolovat zda neobsahuje nějaké temp soubory (případně je zahrnout do `.gitignore`)
  * přegenerovat výsledné PDF (aby repozitář vždy obsahoval aktuální PDF)

### FILES
* `reference.bib` - seznam veškeré literatury
* `/_lib/csplainnat.bst` - podpora českýho typu citací
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
07. `KO` - Metoda větví a mezí. Algoritmy pro celočíselné lineární programování. Formulace optimalizačních a rozhodovacích problémů pomocí celočíselného lineárního programování. Toky a řezy. Multi-komoditní toky.
08. `KO` - Nejkratší cesty. Úloha obchodního cestujícího. Heuristiky a aproximační algoritmy. Metoda dynamického programování. Problém batohu. Pseudo-polynomiální algoritmy.
09. `KO` - Rozvrhování na jednom procesoru a na paralelních procesorech. Rozvrhování projektu s časovými omezeními. Programování s omezujícími podmínkami.

### SI - SOFTWAROVÉ INŽENÝRSTVÍ (od 2011/2012)
01. `TPJ` - Sémantika: operační sémantika, denotační sémantika, pevný bod funkce, vázání jmen, stav, tok a data programu.
02. `TPJ` - Statická sémantika: typy, polymorfní typy, typy vyššího řádu, rekonstrukce (inference) typů, abstraktní typy, moduly, efekty.
03. `NUR` - Teorie HCI, kognitivní aspekty, způsoby interakce, speciální uživatelská rozhraní.
04. `NUR` - Metody návrhu, uživatelské a konceptuální modely.
05. `NUR` - Formální popis uživatelských rozhraní.
06. `NUR` - Pokročilá uživatelská rozhraní (inteligentní uživatelská rozhraní, multimodální uživatelská rozhraní).
07. `NUR` - Metody testování uživatelských rozhraní a jejich vyhodnocování, standardizace.
08. `OSP` - Techniky správy a organizace rozsáhlých softwarových projektů. Nástroje pro správu verzí a vývojových větví zdrojových kódů, nástroje pro automatické generování dokumentace a podporu orientace v rozsáhlých projektech. Infrastruktury zajišťující spolupráci mezi vývojáři navzájem a i s uživateli. Systémy pro sledování a řešení chyb a uživatelskou podporu.
09. `OSP` - Požadavky a pravidla pro tvorbu přenositelného kódu. Organizace projektů a operačních systémů pro splnění přenositelnosti mezi různými architekturami CPU. Konverze vnitřních a vnějších/síťových formátů dat.
10. `AOS` - Co je to architektura zaměřená na služby (SOA)? Základní pojmy, vztah k objektově orientované architektuře. Konceptuální model a formalismy pro modelování SOA.
11. `AOS` - Webové služby. K čemu slouží? Popis a vyhledávání služeb. Co je a k čemu slouží orchestrace a choreografie služeb. Technologie pro implementaci služeb. 
12. `AOS` - Sémantické webové služby. Rozdíl oproti klasickým webovým službám. Výběr sémantických webových služeb, automatická kompozice služeb.
13. `AOS` - Architektura zaměřená na služby (SOA). Kvalita služeb (QoS), výběr založený na QoS, sociální výběr služeb, trust a reputace v otevřených SOA.
14. `TVS` - Kategorizace SW chyb, kriteria korektnosti a pouzitelnosti, spolehlivost SW.
15. `TVS` - Testovaní metodamy bílé a černé skřínky. Strukturální, statická a dynamická analýza. Analýza datových toků. Zátěžové testy.
16. `TVS` - Formální specifikace programu. Verifikace pomocí metod automatického dokazování a metody model-checking.
17. `WA2` - Architektura Java EE, funkce jednotlivých vrstev, životní cyklus standardizovaných komponent Java EE, návrhové vzory využitelné v architektuře webové aplikace.
18. `WA2` - Vhodnost nasazení jednotlivých webových architektur, sdílení dat, perzistence, webové služby a REST, asynchronnost, messaging.
19. `WA2` - Cloud architektury, virtualizace, různá pojetí cloudových řešení, omezení cloudových aplikací, náklady na provoz, vlastnosti aplikací vhodných pro nasazení v cloud architektuře.

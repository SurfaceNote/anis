Analýza systémových požadavků 

25.11.2023 naše společnost byla pozvána zástupci společnosti [název společnosti], panem Klimešem a paní Myhulií, k vývoji pokročilého nástroje pro analýzu výsledků vyhledávání v Google. Hlavním cílem tohoto systému je poskytování uživatelům podrobných a srozumitelných dat o umístění jejich webových stránek ve výsledcích vyhledávání na základě specifických klíčových slov a frází. 

  

Funkční požadavky: 

FR1 (Sběr dat): Backend musí pravidelně provádět web scraping výsledků vyhledávání Google podle zadaných klíčových frází. 

FR2 (Ukládání dat): Sesbírané informace (pozice webů, odkazy, krátké popisy) musí být uloženy v databázi. 

FR3 (Uživatelské rozhraní): Frontend umožňuje uživateli zadávat a spravovat klíčové fráze pro sledování. 

FR4 (Analýza): Uživatelé mohou vidět, jak jsou jejich weby hodnoceny v Google podle zadaných klíčových slov. 

FR5 (Zprávy): Možnost generování zpráv o pozicích webů v čase pro analýzu trendů. 

FR6 (Filtrace výsledků): Možnost filtrovat výsledky vyhledávání podle data, regionu a jazyka. 

FR7 (Upozornění): Automatické zasílání upozornění uživatelům při významných změnách v hodnocení jejich webů. 

FR8 (Integrace se sociálními sítěmi): Možnost analyzovat a zobrazovat údaje o sociálních signálech (např. zmínky na sociálních sítích) pro klíčová slova. 

FR9 (Historie změn): Sledování a ukládání historie změn pozic webů ve výsledcích vyhledávání. 

FR10 (Export dat): Možnost exportovat data a zprávy v různých formátech (např. CSV, PDF). 

FR11 (Uživatelské skupiny): Možnost vytváření skupin uživatelů s různými úrovněmi přístupu. 

FR12 (Podpora několika projektů): Možnost spravovat několik projektů v rámci jednoho účtu. 

FR13 (API pro integraci): Poskytování API pro integraci s dalšími systémy a aplikacemi. 

FR14 (Adaptivní design): Aplikace by měla být přizpůsobena pro použití na různých zařízeních (počítače, tablety, smartphony). 

FR15 (Osobní účet uživatele): Možnost pro uživatele vytvářet a editovat svůj profil, spravovat nastavení upozornění a prohlížet osobní statistiky. 

Nefunkční požadavky: 

NFR1 (Výkon): Systém musí zpracovávat požadavky uživatele a aktualizovat data v reálném čase nebo s minimálním zpožděním. 

NFR2 (Spolehlivost): Systém musí být stabilní a poskytovat přesné výsledky analýzy. 

NFR3 (Škálovatelnost): Systém musí být škálovatelný pro podporu zvýšení objemu dat a počtu uživatelů. 

NFR4 (Bezpečnost): Údaje uživatelů a informace o klíčových slovech musí být chráněny. 

NFR5 (Použitelnost): Rozhraní by mělo být intuitivně srozumitelné a snadno použitelné. 

NFR6 (Kompatibilita): Systém musí být kompatibilní s hlavními prohlížeči a operačními systémy. 

NFR7 (Škálovatelnost databáze): Databáze by měla být navržena pro efektivní práci s velkým objemem dat. 

NFR8 (Křížová platformní kompatibilita): Aplikace by měla podporovat práci na různých platformách a zařízeních. 

NFR9 (Aktualizace dat): Systém by měl pravidelně aktualizovat data, aby byla zachována jejich aktuálnost. 

NFR10 (Dokumentace): Měla by být poskytnuta kompletní technická a uživatelská dokumentace k aplikaci. 

  

Popis doménové analýzy 

V rámci vývoje systému pro analýzu výsledků vyhledávání v Google, je klíčové pochopit různé aspekty a složky, které tvoří strukturu projektu. 

 

 

 

 

 

Diagram 

  

Struktura a Role: 

- Uživatelé: Existují dvě hlavní uživatelské role v systému – běžný uživatel a administrátor. Běžný uživatel má možnost sledovat a analyzovat výsledky vyhledávání, zatímco administrátor může spravovat klíčová slova, uživatele a celkové nastavení systému. 

- Klíčová slova a fráze: Uživatelé mohou přidávat, upravovat a sledovat klíčová slova, která jsou základem pro analýzu výsledků vyhledávání. Systém shromažďuje data o pozici webových stránek ve vyhledáváních na základě těchto klíčových slov. 

- Výsledky vyhledávání: Systém shromažďuje a analyzuje informace o pozicích webových stránek, což umožňuje uživatelům porozumět, jak se jejich stránky umísťují ve vyhledávání. 

- Analýza a zprávy: Uživatelé mohou generovat reporty a získávat analýzy trendů na základě historických dat. Tato funkce je klíčová pro porozumění vývoje pozic webových stránek v čase. 

- Integrace s dalšími systémy: Systém umožňuje export dat a integraci s externími nástroji, což rozšiřuje možnosti analýzy a využití shromážděných informací. 

  

Tento doménový model poskytuje základ pro rozvoj systému, který bude efektivně shromažďovat, zpracovávat a prezentovat data, důležitá pro optimalizaci a strategii v oblasti digitálního marketingu a SEO. 
# [<-](../ "Zpět") Hodnocení architektury MMTA

## Struktura hodnocení

- [Metodika](#metodika "Metodika hodnocení")
- [Hodnocení](#hodnocení "Hodnocení architektury")
- [Souhrn hodnocení](#souhrn "Souhrn hodnocení")

## Metodika

Pro hodnocení architektury bude využita ordinální stupnice, kdy tato tabulka obsahuje slovní ohodnocení a číslené ohodnocení, přičemž číselné ohodnocení bude využito pro posuzování toho, jak zvolená softwarová architektura / řešení splňuje specifickou charakteristiku.

Samotné hodnocení bude uvedeno v tabulce, která bude obsahovat jednotlivé charakteristiky softwarových architektur, dále u každé charakteristiky budou informace, jak moc vybráná architektura / řešení splňuje danou vlastnost na škále 1 - 5 (5 je nejlepší ohodnocení), dále je zde váha důležitosti vlastnostni architektury, protože ne všechny jsou pro aplikaci vhodné, tedy výsledek je součin čísleného ohodnocení a váhy. Také hodnocení každé charakteristiky je doplněno o slovní ohodnocení.

Souhrn výsledků hodnocení charakteristik bude doplněn o slovní ohodnocení architektury, které bude uvedeno v [souhrnu](#souhrn "Souhrn hodnocení") tohoto dokumentu.

| Slovní ohodnocení | Číselné ohodnocení |
|-------------------|--------------------|
| Výborně           | 5                  |
| Dobře             | 4                  |
| Dostatečně        | 3                  |
| Ucházející        | 2                  |
| Nedostatečně      | 1                  |

## Hodnocení

| Charakteristika    | Splňuje | Váha |  Výsledek  |
|--------------------|---------|------|------------|
| Dostupnost         |    5    |  10% |    0,5     |
| Kontinuita         |    4    |  30% |    1,2     |
| Výkonnost          |    5    |  50% |    2,5     |
| Recoverability     |    5    |  10% |    0,5     |
| Reliability        |    4    |  50% |     2      |
| Robustnost         |    5    |  80% |     4      |
| Škálovatelnost     |    5    |  10% |    0,5     |
| Elasticita         |    5    | 100% |     5      |
| Konfigurovatelnost |    4    |  10% |    0,4     |
| Rozšiřitelnost     |    4    |  10% |    0,4     |
| Instalovatelnost   |    5    |  10% |    0,5     |
| Znovupoužitelnost  |    5    |   5% |    0,25    |
| Lokalizace         |    5    |   5% |    0,25    |
| Udržovatelnost     |    5    |  10% |    0,5     |
| Přenositelnost     |    5    |  10% |    0,5     |
| Aktualizovatelnost |    5    |  10% |    0,5     |
| Podpora            |    5    |   5% |    0,25    |
| Zpřístupnění       |    3    |  50% |    1,5     |
| Archivovatelnost   |    5    | 100% |     5      |
| Autentizace        |    5    | 100% |     5      |
| Autorizace         |    5    | 100% |     5      |
| Právní             |    5    |  80% |     4      |
| Soukromí           |    4    |  50% |     2      |
| Zabezpečení        |    4    |  80% |    3.2     |
| Použitelnost       |    5    |  50% |    2.5     |
| Souhrn             |    -    |   -  | 47.95/51.25|

## Souhrn

Na základě poskytnutých hodnot v tabulce hodnocení lze říci, že zvolená architektura dosahuje celkově vysokého ohodnocení. Vlastnosti jako aktualizovatelnost, instalovatelnost, lokalizace, udržovatelnost, a přenositelnost jsou hodnoceny jako výborné, což ukazuje, že systém je dobře navržen z hlediska budoucího rozvoje a adaptace na různé prostředí. Další kritické vlastnosti jako jsou elasticita, archivovatelnost, autentizace a autorizace dostaly plný počet bodů s váhou 100%, což naznačuje, že systém je velmi dobře připraven na zabezpečení a právní požadavky, což je nezbytné pro systém hotelu, který drží informace o svých zákaznících.

Celkově, pokud sčítáme všechny výsledky, dostáváme hodnotu 47.95/51,25. Vážený průměr výsledků je tedy vysoký a naznačuje, že architektura je silná a dobře vyhovuje požadavkům zadání.

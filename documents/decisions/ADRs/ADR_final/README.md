# [<-](./../../README.md "Zpět") ADR_final - Rozhodnutí o výběru architektury

## Status

Přijato

## Kontext

Vzhledem k přísnému časovému rámci pro dokončení projektu před hlavní sezónou a potřebě integrace s několika existujícími systémy, je nezbytné najít rovnováhu mezi rychlostí vývoje, snadností nasazení a dlouhodobou udržitelností projektu. Hledáme řešení, které umožní efektivní vývoj a nasazení, ale zároveň zohledňuje možné budoucí rozšíření a úpravy.

## Rozhodnutí

Po zvážení různých architektonických přístupů bylo rozhodnuto vyvinout systém jako monolitickou aplikaci. Tento přístup bude využívat současné webové technologie jak pro frontend, tak pro backend. Toto rozhodnutí je motivováno potřebou rychlého vývoje a snadného nasazení v rámci našeho omezeného časového rámce.

## Důsledky

### Pozitiva

- Zrychlení vývoje a nasazení díky integraci všech komponent do jedné aplikace.

- Jednodušší správa a ladění s jediným vývojovým a runtime kontextem.

- Nižší počáteční náklady na infrastrukturu a vývoj ve srovnání s mikroservisovou architekturou.

### Negativa

- Omezená škálovatelnost a flexibilita oproti mikroservisové architektuře.

- Vyšší riziko celkového selhání systému v případě chyby v jakékoliv jeho části.

- Možné komplikace při budoucích úpravách nebo při rozdělování aplikace na menší služby.

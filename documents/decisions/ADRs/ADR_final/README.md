# [<-](./../../README.md "Zpět") ADR_final - Rozhodnutí o výběru architektury

## Status

Přijato

## Kontext

Projekt má přísný časový rámec pro dokončení před hlavní sezónou a vyžaduje integraci s několika existujícími systémy. Je potřeba rychle vyvíjet a nasazovat.

## Rozhodnutí

Rozhodnutí: Bylo rozhodnuto vyvinout systém jako monolitickou aplikaci s použitím webových technologií pro frontend a backend.

## Důsledky

### Pozitiva

- Rychlejší vývoj a nasazení, jelikož všechny komponenty jsou integrovány do jediné aplikace.

- Snazší správa a ladění, protože existuje pouze jeden vývojový a runtime kontext.

- Menší počáteční náklady na infrastrukturu a vývoj ve srovnání s mikroservisovou architekturou.

### Negativa

- Omezená škálovatelnost a flexibilita ve srovnání s mikroservisovou architekturou.

- Vyšší riziko celkového selhání systému při chybě v jakékoliv jeho části.

- Potenciální komplikace při budoucích pokusech o rozdělení aplikace na menší služby.

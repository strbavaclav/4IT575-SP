# [<-](../../../README.md "Zpět na přehled systému") Dokumentace monolitické vícevrstvé architektury

## Popis architektury a Systémový přehled

### Jednotná Integrace Funkcí

Tento rezervační systém hotelu je vyvíjen jako jednotný, integrovaný softwarový produkt. Klíčové funkce, jako registrace, rezervace, správa pokoje a kontrola úklidu, jsou implementovány do jedné společné aplikace. Tento přístup umožňuje bezproblémovou integraci různých modulů systému.

### Webová Technologie a Serverová Implementace

Aplikace je navržena s použitím moderních webových technologií, včetně HTML, CSS a JavaScriptu. Na serverové straně je využit Node.js, což poskytuje robustní a efektivní prostředí pro správu serverových procesů.

### Centralizovaná Databáze

Veškeré informace, včetně detailů o pokojích, rezervacích a stavu úklidu, jsou ukládány v centralizované databázi MySQL. Toto uspořádání umožňuje efektivní správu dat a snadný přístup k potřebným informacím.

## Výhody

- Snadnější a rychlejší vývoj, což je klíčové s ohledem na blížící se hlavní sezónu.

- Jednodušší nasazení a údržba, jelikož vše je součástí jedné aplikace.

## Nevýhody

- Může být obtížnější škálovat, pokud počet uživatelů nebo požadavků rychle naroste.

- Větší riziko výpadku celého systému při chybě v jedné části aplikace.

## Sovisející

- [Pohledy](./views/README.md)
  - [Komponenty](./views/components/README.md)
  - [Umístění](./views/deployment/README.md)
- [Hodnocení architektury](./evaluation/README.md)
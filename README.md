# 4IT575 - Semestrální práce
- Tento repositář obsahjuje dokumenty, které se týkají semestrální práce v rámci předmětu 4IT575 - Softwarové architektury
- Software Architecture Document (SAD)

## Autoři práce

- Martin Cháb
- Jiří Kinkor
- David Václavík
- Václav Štrba

## Obsah repositáře

//TODO: obsah doplnit

- [Popis aplikace](#popis-aplikace "Popis aplikace")
- [Otázky na zákazníka](./documents/QA/README.md)
- [Výsledek analýzy zadání](#analýza)
- [Dokumentace architektury č. 1 - Monolitická vícevrstvá architektura](./documents/architectures/MMTA/README.md)
- [Dokumentace architektury č. 2 - SOA](./documents/architectures/SOA/README.md)
- [Architektonická rozhodnutí - ADRs](./documents/decisions/README.md)

## Popis aplikace

Velká společnost zabývající se rezervacemi hotelů chce vytvořit novou generaci systému pro rezervace a správu hotelů, který bude speciálně přizpůsoben pro špičková letoviska a lázně, kde si hosté mohou prohlížet a rezervovat konkrétní pokoje.

**Uživatelé**: Hosté (stovky), zaměstnanci hotelu (méně než 20)

### Požadavky

- Registrace může být provedena přes web, mobilní telefon, telefonní hovor nebo při příchodu.

- Hosté mají možnost rezervovat si buď typ pokoje (standardní, deluxe nebo suite), nebo si vybrat konkrétní pokoj, ve kterém se chtějí ubytovat, prohlížením obrázků jednotlivých pokojů a jejich umístění v hotelu.
- Systém musí být schopen udržovat stav pokoje (rezervovaný, volný, připravený k úklidu atd.).

- Musí mít také nejmodernější funkce pro řízení úklidu, aby bylo možné pracovníky úklidu a údržby nasměrovat do různých pokojů na základě priority a potřeby rezervace pomocí proprietárních zařízení dodaných rezervační společností a připojených k úklidovým vozíkům.

- Standardní rezervační funkce (např. platby, informace o registraci atd.) budou provedeny s využitím stávajícího rezervačního systému.

- Systém bude založen na webových technologiích a bude hostován rezervační společností.

### Další souvislosti

- Hlavní sezóna se rychle blíží, takže systém musí být rychle připraven, jinak budeme muset čekat do příštího roku!.

- Společnost také hodně investuje do nejmodernějších technologií, jako jsou chytré zámky pokojů, které se otevírají pomocí mobilního telefonu.

- Zájem pouze o špičkový trh.

## Analýza

### Driving requirements

- **Hlavní sezóna se blíží** –> Implementace do začátku sezóny (čas)

- **Inovace** –> investice do nejnovějších technologií na trhu (moderní technologie)

### Explicitní požadavky

- Registrace přes web, mobilní telefon, telefonní hovor nebo při příchodu.

- Rezervace standardních, deluxe nebo suite pokojů.

- Možnost vybrat konkrétní pokoj s prohlížením obrázků a umístění v hotelu.

- Udržování stavů pokoje (rezervovaný, volný, připravený k úklidu atd.).

- Správa budoucích rezervací – možnost stornovat

- Automatizované přiřazování úklidových úkolů.

- Integrace s chytrými zámky pro regulaci přístupu úklidového personálu.

- Integrace s existujícím rezervačním systémem (kde je i platební brána).

- Systém založený na webových technologiích.

- Ochrana osobních údajů hostů, shoda s GDPR.

- Kompatibilita s existující infrastrukturou.

- Spuštění systému před začátkem hlavní sezóny.

- Možnost přepínat mezi jazykem a měnou v systému.

### Implicitní požadavky

- Intuitivní a snadné použití systému pro hosty a zaměstnance.

- Schopnost systému zvládnout nárůst rezervací a hostů v průběhu času.

- Vysoká dostupnost a spolehlivost systému, zejména během hlavní sezóny.

- Snadná údržba a aktualizace systému, dlouhodobá podpora.

- Zabezpečení platebních a osobních údajů při online transakcích.

- Možnost budoucích rozšíření a přidání nových funkcí.

### Aplikace v systému

- Nová verze klientské aplikace rezervačního systému
- Backend pro obsluhu klientských aplikací

### Zdroje

- PÍSEK, Slavoj, 2021. Zadání seminární práce z předmětu 4IT575 – Softwarové Architektury. 1. prosinec 2023.
- [Architecture Decision Record Template by Michael Nygard on GitHub](https://github.com/joelparkerhenderson/architecture-decision-record/tree/main/locales/en/templates/decision-record-template-by-michael-nygard)
- [Software Architecture Documentation Template on SEI CMU Wiki](https://wiki.sei.cmu.edu/confluence/display/SAD/Software+Architecture+Documentation+Template)

## Správa dokumentace

Správa dokumentace by měla být v souladu s pravidly nastavenými mezi členy týmu.

## Zvolené architektury

//TODO: udělat ADRka a napárovat

- Monolitic Multi-tier Architecture - MMTA
  - [ADR o využítí MMTA](./dokumentace/EDA/rozhodnutí/2-celkova-architektura/ "ADR o využítí EDA")
- Service Oriented Architecture - SOA
  - [ADR o využítí SOA](./dokumentace/SOA/rozhodnutí/2-celkova-architektura/ "ADR o využítí SOA")

### Výsledná (vybraná) architektura

- Monolitická vícevrstvá architektura
  - [finální ADR o výběru architektury](./dokumentace/EDA/rozhodnutí/2-celkova-architektura/)

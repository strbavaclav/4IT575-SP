# [<-](../../../README.md "Zpět na přehled systému") Dokumentace architektury SOA

## Popis architektury a Systémový přehled

### Rozdělení na Služby

Tento rezervační systém hotelu je navržen s využitím architektury SOA, kde jednotlivé funkce - jako jsou registrace, rezervace, správa pokoje a kontrola úklidu - jsou implementovány jako nezávislé služby. Tyto služby mohou být využívány a kombinovány různými částmi aplikace nebo dokonce i různými aplikacemi.

### Technologie a Komunikace Mezi Službami

Služby jsou vytvořeny s použitím moderních technologií, jako jsou webové API, a mohou být hostovány na různých serverech nebo platformách. Komunikace mezi službami je zajišťována prostřednictvím protokolů jako REST nebo SOAP.

### Flexibilní Uložení Dat

Data jsou spravována decentralizovaně, což znamená, že každá služba může používat vlastní databázi nebo úložiště dat, což umožňuje flexibilitu a optimalizaci pro specifické potřeby jednotlivých služeb.

## Výhody

### Flexibilita a Škálovatelnost

Díky SOA je systém vysoce flexibilní a škálovatelný. Nové služby lze přidávat a stávající upravovat s minimálním dopadem na ostatní části systému. To umožňuje systému růst a adaptovat se na měnící se požadavky a zátěž.

### Odolnost a Spolehlivost

Rozdělení funkcí do nezávislých služeb zvyšuje odolnost celého systému. Chyba v jedné službě nevede nutně k výpadku celého systému, což zvyšuje celkovou spolehlivost aplikace.

## Nevýhody

### Komplexnost a Nároky na Integraci

Architektura SOA může přinést vyšší počáteční komplexnost, zejména v oblasti integrace a správy komunikace mezi službami. To vyžaduje dobře promyšlený design a efektivní řízení.

### Potřeba Pokročilého Monitoringu a Správy

Správa a monitoring takto rozděleného systému může být náročnější, jelikož je třeba sledovat výkon a dostupnost každé individuální služby. Vyžaduje to efektivní nástroje a schopnosti pro správu distribuovaných systémů.

### Správa distribuovaných systémů

Potřeba správy komunikace a koordinace mezi službami.

### Složitější nasazení

Každá služba musí být nasazena a spravována samostatně.

## Functionalita systému

V tomto pohledu je zobrazena funkcionalita rezervačního systému hotelu.

## UML Diagram užití

![Use case](./assets/useCase_diagram.png "Diagram případu užití")

### Vysvětlivky diagramu

- **Use case (případ užití)** - funkce systému - kroužek
- **Actor (aktér)** - osoba / systém, který komikuje s modelovaným systémem - postava
- **Ohraničení systému** - vymezení modelovaného systému - kontejner

## Funkcionality

- **UC1** - Registrace uživatele: Umožňuje hostům vytvořit si účet v systému.
- **UC2** - Přihlášení uživatele: Umožňuje již registrovaným uživatelům přihlásit se do systému.
- **UC3** - Odhlášení uživatele: Umožňuje uživatelům odhlásit se ze systému.
- **UC4** - Prohlédnutí pokoje: Hosté mohou prohlížet dostupné pokoje a jejich detaily.
- **UC5** - Výběr typu pokoje: Hosté si mohou vybrat typ pokoje, který chtějí rezervovat.
- **UC6** - Výběr konkrétního pokoje: Hosté si mohou vybrat a rezervovat konkrétní pokoj.
- **UC7** - Rezervace pokoje: Hosté mohou provést rezervaci vybraného pokoje.
- **UC8** - Storno rezervace: Umožňuje hostům stornovat již provedenou rezervaci.
- **UC9** - Správa rezervací: Zaměstnanci mohou spravovat rezervace, včetně jejich úprav a storna.
- **UC10** - Zobrazení stavu pokoje: Systém zobrazuje aktuální stav pokoje.
- **UC11** - Změna stavu pokoje: Zaměstnanci mohou měnit stav pokoje (např. z 'volný' na 'rezervovaný').
- **UC12** - Self check-in / check-out: Umožňuje hostům provést check-in nebo check-out bez asistence personálu.
- **UC13** - Změna jazyka / měny: Hosté mohou změnit jazyk a měnu zobrazení v systému.
- **UC14** - Zařízení úklidu pokoje: Systém umožňuje zaměstnancům spravovat procesy úklidu.
- **UC15** - Provedení platby: Integrace s existujícím rezervačním systémem pro zpracování plateb.
- **UC16** - Správa registrací: Umožňuje zaměstnancům spravovat registrace uživatelů.
- **UC17** - Odemknutí / zamknutí pokoje: Systém umožňuje zaměstnancům ovládat zámky pokojů.
- **UC18** - Správa systému: Administrátoři mohou spravovat a konfigurovat celý rezervační systém.

## Sovisející

- [Pohledy](./views/README.md)
  - [Komponenty](./views/components/README.md)
  - [Umístění](./views/deployment/README.md)
- [Hodnocení architektury](./evaluation/README.md)

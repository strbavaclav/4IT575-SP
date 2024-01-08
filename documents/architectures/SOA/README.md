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

## Katalog komponent

### název

popis

- část

## Sovisející

- [Pohledy](./views/README.md)
  - [Komponenty](./views/components/README.md)
  - [Umístění](./views/deployment/README.md)
- [Hodnocení architektury](./evaluation/README.md)

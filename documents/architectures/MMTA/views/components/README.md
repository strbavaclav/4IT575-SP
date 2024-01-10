# [<-](./../README.md "Zpět") Component View

V tomto pohledu jsou zobrazeny komponenty rezervačního systému hotelu dle architektury MMTA (Monolitic Multi-tier architecture).

## UML Diagram komponent

![Komponent diagram](./../../assets/component_diagram_MMTA.png "Diagram komponent")

## Katalog komponent

Pro potřeby hotelu byla zvolena architektura, která se skládá ze sedmi vrstev: prezentační vrstva, byznys logika, datová vrstva, integrační vrstva, externí připojení komponent a poslední vrstvou je infraktruktura.

### Prezentační vrstva

Tato vrstva umožňuje uživatelům interagovat se systémem. Interakce probíhá pomocí webového prohlížeče, který může být zobrazen ve všech možných zařízeních díky tomu, že je responzivní. Zobrazení a samotnou interakci zajišťuje webový klient.

### Byznys logika

Vrstva byznys logiky zpracovává obchodní pravidla, výpočty a logiku. Odehrává se zde veškeré důležité rozhodování celého systému.

### Datová vrstva

Datová vrstva slouží k ukládání veškerých informací. V případě této architektury je to pomocí MySQL databáze a pak externího úložiště dokumentů. Jsou zde uloženy například informace o rezervacích až po detaily jednotlivých pokojů, které jsou hotelem nabízeny.

### Integrační vrstva

Tato vrstva je spojkou mezi vnitřní funkcionalitou celého systému a externími službami. Stará se o to, aby mezi sebou jednotlivé komponenty komunikovali nezávisle na jejich technologii. Je zde umístěn middleware, který je zde jako zázemí pro plynulou spolupráci mezi různými systémy a platformami.

### Externí připojení komponent

Rezervační systém je připojen k některým službám, které nejsou součástí našeho systému, ale jsou externí komponentou (jako je například připojení IoT zařízení). Tato vrstva také připojuje stávající rezervační systém. Díky této vrstvě je možné, aby fungovaly chytré vozíky či systém chytrých zámků v hotelu.

### Infrastruktura

Tato nejnižší vrtsva je fyzický základ systému, který zajišťuje, že všechny technologické komponenty jsou bezpečně hostovány, chráněny a propojeny pro neustálý provoz. Jsou zde umístěny veškeré servery včetně jejich konfigurací, síťové komponenty a firewall pro bezpečný síťový provoz.

# [<-](../../README.md "Zpět na přehled systému") Dotazy na zákazníka

## Obsah

1. [Jaké přesně funkce očekáváte od systému pro řízení úklidu?](#1-jaké-přesně-funkce-očekáváte-od-systému-pro-řízení-úklidu)
2. [Jsou zde specifické automatizační procesy nebo integrace s externími zařízeními?](#2-jsou-zde-specifické-automatizační-procesy-nebo-integrace-s-externími-zařízeními)
3. [Budou stavy hotelového pokoje předem dány nebo si je každý zaměstnanec může vymýšlet?](#3-budou-stavy-hotelového-pokoje-předem-dány-nebo-si-je-každý-zaměstnanec-může-vymýšlet)
4. [Potřebujete integraci s externími systémy nebo službami, jako jsou systémy třetích stran pro správu hotelů?](#4-potřebujete-integraci-s-externími-systémy-nebo-službami-jako-jsou-systémy-třetích-stran-pro-správu-hotelů)
5. [Jaký je očekávaný počet rezervací a uživatelů systému (např. hostů) v krátkodobém a dlouhodobém horizontu?](#5-jaký-je-očekávaný-počet-rezervací-a-uživatelů-systému-např-hostů-v-krátkodobém-a-dlouhodobém-horizontu)
6. [Existují specifické požadavky na škálovatelnost systému?](#6-existují-specifické-požadavky-na-škálovatelnost-systému)
7. [Jaké jsou vaše požadavky na bezpečnost dat a ochranu soukromí, zejména s ohledem na osobní údaje hostů?](#7-jaké-jsou-vaše-požadavky-na-bezpečnost-dat-a-ochranu-soukromí-zejména-s-ohledem-na-osobní-údaje-hostů)
8. [Jaké jsou plány na budoucí rozšíření nebo aktualizace systému?](#8-jaké-jsou-plány-na-budoucí-rozšíření-nebo-aktualizace-systému)
9. [Jaké jsou očekávání ohledně udržitelnosti a aktualizace systému?](#9-jaké-jsou-očekávání-ohledně-udržitelnosti-a-aktualizace-systému)
10. [Jaký je rozpočet pro vývoj a provoz systému?](#10-jaký-je-rozpočet-pro-vývoj-a-provoz-systému)
11. [Je od systému vyžadováno, aby podporoval více jazykových mutací a více měn?](#11-je-od-systému-vyžadováno-aby-podporoval-více-jazykových-mutací-a-více-měn)
12. [Může i host manipulovat se svou rezervací (Například přesunout či stornovat)?](#12-může-i-host-manipulovat-se-svou-rezervací-například-přesunout-či-stornovat)
13. [Měl by systém umožňovat pokročilé funkce jako je self-check-in/check-out?](#13-měl-by-systém-umožňovat-pokročilé-funkce-jako-je-self-check-incheck-out)

## Otázky

### 1. Jaké přesně funkce očekáváte od systému pro řízení úklidu?

- Očekáváme, že systém bude schopen automaticky přiřazovat úklidové úkoly na základě stavu pokoje a rezervací. systém drží stav pokoje (rezervovaný, uklizený apod.). Automaticky vyhodnocuje kdy je potřeba uklidit (je 12h, ve 14h má přijít host, ale stav pokoje je - neuklizený) - v tu chvíli zasílá automaticky notifikaci na aktivního zaměstnance úklidu.

### 2. Jsou zde specifické automatizační procesy nebo integrace s externími zařízeními?

- Chceme integraci s chytrými zámky pokojů, aby bylo možné otevírat zámky pomocí systému. Dále již výše zmíněný proces automatizace úklidu pokojů.

### 3. Budou stavy hotelového pokoje předem dány nebo si je každý zaměstnanec může vymýšlet?

- Stavy hotelového pokoje jsou předem dány. V případě změny bude systém aktualizován na nový požadavek s novou verzí.

### 4.Potřebujete integraci s externími systémy nebo službami, jako jsou systémy třetích stran pro správu hotelů?

- Nepotřebujeme.

### 5. Jaký je očekávaný počet rezervací a uživatelů systému (např. hostů) v krátkodobém a dlouhodobém horizontu?

- Počet rezervací by měl být v prvním roce v řádech stovek.
- V dlouhodobém horizontu očekáváme stabilní poptávku z důvodu zacílení na špičkovou klientelu.

### 6. Existují specifické požadavky na škálovatelnost systému?

- Systém by měl být škálovatelný, aby zvládl větší množství dotazů v případě přidání nových služeb. Neočekáváme navýšení užívání větším množstvím uživatelů v dlouhodobém horizontu.

### 7. Jaké jsou vaše požadavky na bezpečnost dat a ochranu soukromí, zejména s ohledem na osobní údaje hostů?

- Je nezbytné zajistit ochranu osobních údajů hostů a dodržování právních norem, včetně GDPR. Bezpečnost dat a transakcí je pro nás klíčová.

### 8. Jaké jsou plány na budoucí rozšíření nebo aktualizace systému?

- Očekáváme, že systém bude průběžně aktualizován a rozšiřován, aby zahrnoval nové funkce a technologie v závislosti na poptávce klientely. Například rezervace doplňkových služeb hotelu.

### 9. Jaký je rozpočet pro vývoj a provoz systému?

- Rozpočet je flexibilní, ale očekáváme efektivní využití prostředků.

### 10. Je od systému vyžadováno, aby podporoval více jazykových mutací a více měn?

- Od systému očekáváme češtinu a angličtinu. Požadujeme zobrazování cen služeb v českých korunách a eurech.

### 11. Může i host manipulovat se svou rezervací (Například přesunout či stornovat)?

- Stornovat může za poplatek pomocí našeho systému. Přesouvat nemůže.
- Stornovat je možné také telefonicky.

### 12. Měl by systém umožňovat pokročilé funkce jako je self-check-in/check-out?

- Tato služba by byla určitě přínosem, ale není to pro nás momentálně prioritou.

### 13. Otázka na vozíky jak mají fungovat

- Přihlásíš se pod nějakou rolí do systému a například na kliknutí pokud má práva ti to dovolí otevřít ten pokoj

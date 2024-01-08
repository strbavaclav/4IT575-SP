# [<-](./../../README.md "Zpět") ADR_03 - Rozhodnutí o ukládání obrázků a větších souborů

## Datum: 10. 1 . 2023

## Status

Přijato

## Kontext

S rostoucími potřebami ukládání velkých souborů, jako jsou obrázky a multimediální obsah, jsme čelili výzvě najít řešení, které je bezpečné, škálovatelné a efektivní z hlediska nákladů. Bylo důležité vybrat platformu, která může podporovat rychlý přístup k datům a zároveň zajistit jejich bezpečnost.

## Rozhodnutí

Po zvážení různých cloudových úložišť jsme se rozhodli pro Amazon Web Services (AWS) S3 pro ukládání našich obrázků a větších souborů. AWS S3 bylo vybráno kvůli jeho vysoké dostupnosti, odolnosti vůči selhání, a škálovatelnosti, což nám umožní efektivně spravovat a přistupovat k našim datům.

## Důsledky

Toto rozhodnutí má několik důležitých důsledků. Nejvýznamnější je schopnost AWS S3 škálovat podle našich potřeb, což umožňuje efektivní správu nákladů, a to i přes potenciálně vysoké náklady na přenos dat a úložný prostor. Dále poskytuje robustní bezpečnostní funkce, které zajišťují bezpečnost našich dat. Nicméně musíme pečlivě monitorovat a řídit náklady spojené s ukládáním a přenosem dat, aby se zabránilo neočekávaným výdajům.

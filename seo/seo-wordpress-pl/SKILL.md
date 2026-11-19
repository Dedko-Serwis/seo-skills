---
name: seo-wordpress-pl
description: Techniczny audyt SEO WordPress z Gutenberg i LiteSpeed Cache, obejmujący indeksowanie, sitemap, canonical, dane strukturalne, wydajność i konflikty wtyczek.
metadata:
  version: 0.1.0
  author: Dedko-Serwis
---

# WordPress SEO — audyt PL

## Zakres
Przeanalizuj wskazaną witrynę WordPress, uwzględniając Gutenberg, LiteSpeed Cache i wtyczki SEO, jeśli ich obecność została potwierdzona.

## Kroki
1. Odczytaj stronę główną, kluczowe podstrony, robots.txt i wskazaną mapę witryny. Sprawdź odpowiedzi HTTP, canonical, noindex i przekierowania.
2. Oceń tytuły, opisy, H1-H3, obrazy i teksty alternatywne, linkowanie wewnętrzne i breadcrumbs.
3. Sprawdź, czy dane JSON-LD nie są dublowane przez motyw, wtyczkę i kod własny.
4. Oceń możliwe konflikty cache/minifikacji z dynamicznymi elementami; nie wyłączaj wtyczek bez zgody.
5. Jeżeli dostępne są pomiary PageSpeed lub CrUX, przedstaw wartości i datę. W przeciwnym razie wskaż je jako wymagające pomiaru.
6. Zaproponuj minimalne, odwracalne poprawki z testem regresji i sposobem wycofania.

## Wynik
Tabela problemów z dowodem, URL, priorytetem, proponowaną zmianą i metodą sprawdzenia. Nie deklaruj wyników indeksowania bez GSC.

## Ograniczenia
Bez wyraźnej akceptacji nie publikuj zmian, nie czyść cache produkcyjnego, nie zmieniaj ustawień indeksowania, nie edytuj plików serwera i nie instaluj wtyczek.

# Krølle-Spille

Website for musikforeningen **Krølle-Spille** på Bornholm, der arrangerer gratis koncerter på Tejn Havn. Sitet bruges i forbindelse med ansøgning om økonomisk støtte fra Bornholms Regionskommune.

## Indhold

- `index.html` – hele websitet (one-pager, selvstændig HTML med inline CSS)
- `data/koncerter.json` – strukturerede data over afholdte og kommende koncerter

## Sektioner

1. Om foreningen
2. Formålsparagraf (vedtægtsuddrag, §1–§5)
3. Afholdte koncerter 2022–2026 + kommende koncerter
4. Kontakt

Sektionen "Derfor søger vi støtte" findes i HTML'en, men er skjult via CSS-reglen `.stotte-section{display:none}` i `index.html`. Fjern den linje for at vise sektionen igen.

## Hosting

Sitet er statisk og kan hostes hvor som helst (Render Static Site, GitHub Pages m.m.). Ingen build-proces – deploy mappen som den er.

## Kilder

Koncertdata er indsamlet fra [Brewery Bar & Shop på Facebook](https://www.facebook.com/penyllanbarandshop) og [penyllan.com/events](https://penyllan.com/events/).

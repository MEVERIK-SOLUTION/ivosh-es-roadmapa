# ES MPO Portál – Ivoš | WHC s.r.o.

Interaktivní portál pro proces získání oprávnění energetického specialisty MPO.

## Funkce

- **Dashboard** — přehled stavu, chybějící dokumenty, progress, nadcházející události
- **Pipeline kroků** — interaktivní 6-krokový průvodce procesem žádosti
- **Správa dokumentů** — upload/download souborů dle kroků (IndexedDB v prohlížeči)
- **Kalendář** — termíny zkoušek, školení, deadlines
- **Zkoušky & studium** — studijní materiály, poznámky, stav zkoušek
- **Export/Import** — záloha a obnova dat (JSON)

## Architektura

Celý portál je jeden `index.html` — SPA (Single Page Application) bez backendu.

**Úložiště:** IndexedDB v prohlížeči — soubory se ukládají lokálně.  
**Záloha:** Export/Import v patičce sidebaru — JSON soubor se vším včetně souborů.

## Deploy

Automaticky přes GitHub Actions při push do `main`.

**URL:** https://meverik-solution.github.io/ivosh-es-roadmapa/

## Struktura

```
index.html                    # Kompletní portál
.nojekyll                     # Vypnutí Jekyll na GitHub Pages
README.md                     # Tento soubor
.github/workflows/deploy.yml  # Automatický deploy
```

## Klíčové zdroje

- [MPO – Energetičtí specialisté](https://mpo.gov.cz/cz/energetika/uspory-energie/energeticti-specialiste/)
- [SEI – Termíny zkoušek](https://sei.gov.cz/?p=9686)
- [ENEX – Seznam ES](https://www.mpo-enex.cz/experti)

## Autor

Připravil Matěj Kocanda, MBA · WHC s.r.o. © 2026

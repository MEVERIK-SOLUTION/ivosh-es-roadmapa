# Roadmapa: Energetický specialista MPO – Ivoš

Interaktivní průvodce procesem získání oprávnění energetického specialisty MPO (PENB – typ B) pro WHC s.r.o.

## O projektu

Standalone HTML aplikace bez závislostí. Funguje jako interaktivní pipeline s checklistem, klíčovými informacemi a přímými odkazy na formuláře MPO, SEI a další zdroje.

**Pro koho:** Ivoš – budoucí společník WHC s.r.o., uchazeč o oprávnění ES MPO  
**Připravil:** Matěj Kocanda, MBA – WHC s.r.o.  
**Aktualizováno:** Březen 2026

## Obsah

Aplikace pokrývá 6 kroků:

1. Shromáždění dokladů (vysvědčení, doložení praxe)
2. Správní poplatek (platba přes internet banking)
3. Podání žádosti na MPO (datová schránka ID: bxtaaw4)
4. Studium a příprava na zkoušku (2–3 měsíce)
5. Odborná zkouška – den D (MPO Praha)
6. Rozhodnutí MPO a zápis do Seznamu ES

## Nasazení

Stránka je nasazena přes GitHub Pages na adrese:  
**https://[USERNAME].github.io/ivosh-es-roadmapa/**

Při každém commitu do větve `main` se automaticky spustí GitHub Actions workflow a stránka se aktualizuje do ~2 minut.

## Struktura repozitáře

```
ivosh-es-roadmapa/
├── index.html          # Hlavní interaktivní aplikace (vše v jednom souboru)
├── README.md           # Tento soubor
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Actions – automatický deploy na Pages
```

## Klíčové zdroje

- [MPO – Jak se stát energetickým specialistou](https://mpo.gov.cz/cz/energetika/uspory-energie/energeticti-specialiste/jak-se-stat-energetickym-specialistou/jak-se-stat-energetickym-specialistou--277126/)
- [SEI – Termíny zkoušek 2026](https://sei.gov.cz/?p=9686)
- [ENEX – Seznam energetických specialistů](https://www.mpo-enex.cz/experti)
- [AEA – Přípravný kurz](https://www.aea.cz/vzdelavaci-akce/osmidenni-pripravny-kurz-ke-slozeni-zkousek)
- [Czech Point – aktivace datové schránky](https://www.czechpoint.cz/public/)

## Právní poznámka

Interní dokument WHC s.r.o. Informace vycházejí z platné legislativy k březnu 2026 (zákon č. 406/2000 Sb., vyhláška č. 280/2023 Sb. ve znění č. 416/2025 Sb.). Před podáním žádosti ověřte aktuální podmínky na webu MPO.

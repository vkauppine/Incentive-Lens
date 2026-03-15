# Incentive Lens — CLAUDE.md

## Projektin kuvaus

Quarto-pohjainen blogi GitHub Pagesissa. Taloustiede ja kannustinanalyysi suomeksi.
GitHub: vkauppine/Incentive-Lens (vkauppine.github.io/Incentive-Lens)

## Kieli ja tyyli

- Kaikki julkaistu sisältö **suomeksi**
- Selkeä, argumentatiivinen proosa — ei akateeminen mutta teoreettisesti perusteltu
- Lukija oletetaan älykkääksi mutta ei välttämättä ekonomistiksi
- Älä käytä swedes­ismiä "toimesta" äläkä finglish-verbejä

## Blogi-identiteetti

Taloudellisten kannustinrakenteiden analyysi — miten kannustimet muovaavat käyttäytymistä
yksilö-, yritys- ja instituutiotasolla. Markkinatalouden näkökulma joka tunnistaa
rakenteelliset ongelmat.

## Sisältöalueet

- Rahapolitiikka ja keskuspankkien kannustimet (EKP, Fed)
- AI:n talousvaikutukset ja tuottavuus (Brynjolfsson, Nordhaus, Jones)
- Suomalaisten pk-yritysten näkökulma makrokehitykseen
- Singaporen talousmallin analyysi
- Alankomaiden 1600-luvun talousmalli (kiinnostuksen kohde, tulevat postit)

## Tiedostorakenne

- Postit: `.qmd`-formaatti YAML-headereineen
- Nimeämiskäytäntö: `aihe_v[versio].qmd` tai `aihe_indeksi.qmd`
- Hakemisto: `posts/`

## YAML-header malli

```yaml
---
title: "Otsikko tähän"
date: "YYYY-MM-DD"
categories: [rahapolitiikka, ai, pk-yritykset]
description: "Lyhyt kuvaus."
---
```

## Julkaistuja tai luonnosvaiheessa olevia postauksia (referenssi)

- EKP:n joukko-osto-ohjelmat ja finanssidisipliinin kannustimet (Matti Viren -inspiraatio)
- Kevin Warsh / Fed ja AI-tuottavuusargumentti (kannustinrakenteen kehys)
- AI-singulariteetti talousteorian kautta (Nordhaus, Jones, heikot lenkit)
- AI-tuottavuusparadoksit JD-R ja Bayesilainen workflow
- Citrini Research 2028 -skenaariokritiikki suomalaisen pk-yrityksen näkökulmasta
  (tiedosto: tekoaly_kysyntashokki_v4.md)
- Singaporen talousmalli R/WDI-visualisaatioilla

## Visualisoinnit

- R-koodia käytetään datavisualisaatioihin (WDI-paketti World Bank -dataan)
- Kuviot integroidaan suoraan Quarto-dokumenttiin
- Tyyliohje: selkeä, minimalistinen

## Tekniset huomiot

- GoatCounter-analytiikka: vkauppine.goatcounter.com
- Giscus-kommentit käytössä
- RSS-syöte konfiguroitu

## Tyypilliset tehtävät

- Uuden postauksen luominen: tee `.qmd` oikealla headerilla ja argumenttirakenne
- Talouslogiikan tarkistus: onko kannustinmekanismi eksplikoitu selkeästi?
- Kieliasu: tarkista suomen oikeellisuus, vältä toimesta/finglish-ongelmat
- R-koodin integrointi: visualisaatiot Quarto code chunkeihin

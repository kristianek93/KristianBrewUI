# KristianBrewUI
Tizen TV UI pro instalaci/updaty z GitHub Releases (asset `*.wgt`).

## Jak to funguje
- UI načte repozitáře uživatele `kristianek93`
- filtruje repa, která mají:
  - `kbrew.json` v rootu **nebo**
  - `latest release` s assetem `*.wgt`
- nabídne Install/Update

## Instalace
- Buildni WGT (Tizen CLI) a nainstaluj přes TizenBrew nebo přes klasické Tizen nástroje.

## Poznámka
"Install" tlačítko se nejdřív pokusí použít lokální install service (pokud existuje),
jinak otevře download link jako fallback.

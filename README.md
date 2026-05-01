# ChillTreasuries — treasuries longues US, posées.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE)
[![Phase amorçage](https://img.shields.io/badge/phase-amor%C3%A7age-yellow.svg)](#)
[![Galaxie InvestChill](https://img.shields.io/badge/galaxie-InvestChill-informational.svg)](https://github.com/investchill)

**ChillTreasuries** est le sibling de la galaxie [InvestChill](https://github.com/investchill)
dédié à la classe **treasuries longues US** (long-duration US Treasury bonds). Il s'inscrit
dans le folio All-Weather [ChillFOLIO](https://github.com/investchill/chillfolio) en couvrant
le quadrant macro **croissance basse / inflation basse** — le quadrant récessionniste classique.

> ⚠️ **Phase amorçage.** Le projet est tout neuf. Le signal mensuel mécanique, le choix
> d'ETF concret et le backtest sibling-spécifique restent à figer.

---

## Cadre

- **Quadrant macro adressé** : croissance basse, inflation basse (récession sans inflation).
- **Cadre fiscal France** : PEA non-éligible — CTO uniquement (PFU 31,4 % en 2026 sur coupons
  et plus-values). Pénalisant fiscalement, mais pas substituable par les treasuries longues
  Euro AAA pour la diversification.
- **Mécanique attendue** : signal mensuel ON/OFF, anti-overfit (1-2 paramètres maximum,
  plateau de stabilité, walk-forward), gestion explicite des régimes inflation shock
  type 2021-2023.

---

## À venir

Le sibling produira son propre signal mensuel mécanique et publiera les résultats
backtestés sur sa page publique. Cible : opérationnel avant la **1ʳᵉ revue annuelle
ChillFOLIO du 2027-01-01**.

---

## Liens

- [ChillFOLIO](https://github.com/investchill/chillfolio) — folio umbrella ([landing](https://investchill.github.io/chillfolio/)).
- [ChillBTC](https://github.com/investchill/chillbtc) — sibling crypto live ([landing](https://investchill.github.io/chillbtc/)).

---

## License et disclaimer

Code et contenu sous licence **[CC BY-NC-SA 4.0](LICENSE)** — usage non-commercial.

**ChillTreasuries n'est pas un conseil en investissement.** Les performances passées ne
préjugent pas des performances futures. Tu es seul responsable de tes décisions.

> © 2026 ChillTreasuries — partie de la galaxie [InvestChill](https://github.com/investchill).

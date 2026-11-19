# Kumbu24

Concept prototype for **Kumbu24** ("kumbu por dia"), a daily micro-loan with automatic savings, proposed for a pilot with Banco de Fomento Angola (BFA).

This is a working concept for discussion. It is not a commercial offer, not an official BFA communication and not legal advice. Rates, limits, reputation levels, API names and the pilot calendar are illustrative and will be calibrated in the pilot. The regulatory reading must be confirmed by BFA's legal team.

## Contents

| Path | What it is |
| --- | --- |
| `index.html` | Three-tab concept page in Portuguese: **Para o cliente** (ad plus day and 30-day simulators), **Para o banco** (pilot card, architecture explorer, 12-step flow, integrations, 24-week plan, pilot calculator) and **Para o Governo** (ENIF targets, contribution calculator, formalisation ladder) |
| `docs/modelo-de-negocio-bfa-pt.md` | Recommended business model (PT-PT): BFA as anchor bank, platform building blocks, Cofre e Bolso, daily-loan pricing, BNA rules, phasing, delivery model, open questions |
| `docs/rapyd-decreto-89-23-analysis-en.md` | Rapyd executive summary, Decreto Presidencial 89/23 and Angola market analysis (EN). Written before BFA was chosen, so it uses BAI as the example anchor bank |
| `docs/img/` | Diagrams used in the two documents |

## Viewing the page

Open `index.html` in any modern browser. There is no build step and no server. The page loads its fonts from Google Fonts and falls back to system fonts offline. Everything else, including the simulators, is inline.

The repository is meant to stay **private**: the page names BFA and mocks a consumer ad for a product that does not exist yet.

## Key decisions (19 November 2026)

- Anchor bank: BFA. The loan book stays on BFA's balance sheet only.
- BFA's internal team leads the project; the external implementer is still to be selected.
- Product: 1-day loans up to the equivalent of USD 100 (about Kz 90 000), repaid automatically from the day's sales.
- KYC requires a Bilhete de Identidade (BI).
- The Cofre (automatic savings) works as collateral, as reputation and as access to lower rates.

## Main sources

- BNA Aviso n.º 14/16 (credit information duties) and Aviso n.º 5/17 (Multicaixa), via [LEX.AO](https://lex.ao/)
- Decreto Presidencial n.º 89/23 (microcredit companies and operators), via [LEX.AO](https://lex.ao/docs/presidente-da-republica/2023/decreto-presidencial-n-o-89-23-de-31-de-marco/)
- BFA Market Discipline Report 2025, BFA Tecla leaflet and BFA price list, via [bfa.ao](https://www.bfa.ao/)
- Angolan government via ANGOP (ENIF, July 2026), Expansão, VerAngola and Forbes África Lusófona

Each document lists its full sources at the end.
